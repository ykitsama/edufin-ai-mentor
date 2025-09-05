EduFin AI Mentor

Offline-first **Financial Literacy Progressive Web App (PWA)**.  
Learn budgeting, avoid scams, and earn rewards — even with low/no internet.

Features
- Interactive lessons (download & use offline)
- Gamified quizzes with IndexedDB storage
- AI Mentor (offline fallback + online AI API)
- Rewards dashboard with badges
- Scam Shield corner for fraud awareness

Tech Stack
- **Frontend**: React (PWA, IndexedDB)
- **Backend**: Node.js + Express
- **Database**: MongoDB (sync), IndexedDB (offline)
- **AI**: OpenAI API (online) + cached Q&A (offline)

Setup
```bash
git clone https://github.com/ykitsama/edufin-ai-mentor.git
cd edufin-ai-mentor
npm install
cd client && npm install
