# CrowdCheck

### Real-time transport crowd reporter

**Know before you go.** Community-powered, photo-verified crowd reports for buses and trains.

[![Stack](https://img.shields.io/badge/Stack-React%20%2B%20Firebase-orange)](#)
[![Auth](https://img.shields.io/badge/Auth-Google%20OAuth-blue)](#)

---

## What is CrowdCheck?

CrowdCheck is a civic-tech web platform where commuters report real-time crowd levels on public transport (buses, trains, metros).

Every report requires **photo proof**. Fake reports can lead to permanent account bans.

---

## Features

| Feature | Status |
|---------|--------|
| Google OAuth (Firebase Auth) | ✅ |
| Photo proof upload (Firebase Storage) | ✅ |
| Bus & train crowd reporting | ✅ |
| Live real-time feed | ✅ |
| Community upvote / flag | ✅ |
| Fake report → account ban | ✅ |
| Search by route / vehicle number | ✅ |
| Crowd level meter (1–5) | ✅ |
| Mobile-first UI | ✅ |

---

## Tech stack

- **Frontend:** React
- **Auth:** Firebase Authentication (Google)
- **Storage:** Firebase Storage
- **Database:** Firestore
- **Deploy:** Vercel

---

## Getting started

```bash
git clone https://github.com/sayan9168/CrowdCheck-Real-time-Transport-Crowd-Reporter.git
cd CrowdCheck-Real-time-Transport-Crowd-Reporter

npm install
npm run dev
```

Configure Firebase credentials as required by the project env files before production use.

```bash
npm run build
# deploy with Vercel or your preferred host
```

---

## Anti-fake policy

- Photo of the vehicle interior required
- Community can flag suspicious reports
- Repeated fakes → permanent ban on the Google account

---

## Author

[Sayan Mahata](https://github.com/sayan9168) · Sayanox Private Limited  
Email: sm6881164@gmail.com
