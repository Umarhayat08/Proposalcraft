# ✨ ProposalCraft AI

**ProposalCraft AI** is a modern, AI-powered proposal and outreach generator built with **React**, **Vite**, and the **Google Gemini API** (`gemini-2.0-flash`)[cite: 1, 4]. Designed for freelancers, consultants, and agencies, it transforms job descriptions and your personal bio into tailored, high-converting proposals in seconds.

---

## 🚀 Key Features

- **Multi-Platform Tailoring:** Generate custom outreach for **Upwork Cover Letters**, **Fiverr Buyer Requests**, **LinkedIn Outreach**, and **Cold Emails**.
- **Adjustable Tone Controls:** Switch between *Persuasive & Direct*, *Short & High Impact*, *Formal & Corporate*, and *Conversational* styles.
- **Persistent Profile & Bio:** Save your portfolio summary and experience once so every generated proposal automatically highlights your relevant strengths.
- **Local-First API Key Storage:** Bring your own Google AI Studio Gemini API key, stored securely in your browser's `localStorage` with zero backend exposure.
- **Proposal History & Export:** Copy proposals with one click, download them as `.txt` files, or save winning drafts to your local history[cite: 4].
- **Modern Glassmorphic UI:** Dark-mode interface featuring ambient motion graphics, animated loading skeletons, and non-intrusive toast notifications.

---

## 🛠️ Tech Stack

- **Frontend:** React 18+, JSX, CSS3 Keyframe Animations[cite: 1, 4]
- **Build Tool:** Vite[cite: 1]
- **AI Engine:** Google Gemini API (`gemini-2.0-flash`)[cite: 4]
- **Storage:** Browser `localStorage`[cite: 4]

---

## 📂 Project Structure

```text
ProposalCraft-ai/
├── proposalcraft-app/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── App.css
│   │   ├── App.jsx        # Main UI, Gemini integration & local storage logic
│   │   ├── index.css
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
└── README.md
