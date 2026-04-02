🚇 CrowdCheck — Real-time Transport Crowd Reporter
Know before you go. Community-powered, photo-verified crowd reports for buses and trains worldwide.
�
�
�
�
🌍 What is CrowdCheck?
CrowdCheck is a civic-tech web platform where commuters report real-time crowd levels in public transport — buses, trains, metros — across all countries worldwide.
Every report requires photo proof. Submit a fake? Your account is permanently banned. No exceptions.
✨ Features
Feature
Status
🔐 Google OAuth Login (Firebase Auth)
✅
📸 Photo proof upload (Firebase Storage)
✅
🚌 Bus & 🚆 Train crowd reporting
✅
🌍 All countries support
✅
📡 Live real-time feed
✅
👍 Community upvote / flag system
✅
🚫 Fake report = Account ban
✅
🔍 Search by route / vehicle number
✅
📊 Crowd level meter (1–5 scale)
✅
📱 Mobile-first responsive design
✅
🛠️ Tech Stack
Frontend: React 18 + JSX (single-file component)
Auth: Firebase Authentication (Google OAuth)
Storage: Firebase Storage (photo proof uploads)
Database: Firebase Firestore (reports, users, ban records)
Deployment: Vercel
Design: Custom dark futuristic UI (no UI library)
🚀 Getting Started
1. Clone the repo
git clone https://github.com/sayan9168/crowdcheck.git

4. Run locally
npm run dev
5. Deploy to Vercel
npm run build
vercel --prod
🚫 Anti-Fake Policy
CrowdCheck has a strict zero-tolerance policy for false reports:
Every report must include a photo of the actual vehicle interior
Community members can flag suspicious reports
Repeated fake reports result in permanent account ban
Banned user IDs are stored in Firebase and cannot create new accounts with the same Google account
📬 Contact
Sayan — Founder & CEO, Sayanox Private Limited
📧 sm6881164@gmail.com
🌐 sayanox-website.vercel.app
📄 License
© 2025 Sayanox Private Limited. All rights reserved.
Built with ❤️ by Sayan.
