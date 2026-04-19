# Road Wallet

A real-time group travel expense tracker. Add travellers,
log expenses by category, and instantly see how much
each person owes — synced live across all devices via Firebase.

**[Live Demo](#)** ← add Netlify URL once deployed

---

![Road Wallet Screenshot](screenshot.png)

---

## Features

- Add and remove travellers
- Log expenses by category: food, gas, accommodations, sightseeing
- Automatically splits total costs equally between travellers
- Real-time sync across devices using Firebase Realtime Database
- Expense history with delete functionality
- Data persists across sessions

---

## Built with

- Vanilla JavaScript (ES6 modules)
- Firebase Realtime Database (real-time data sync)
- Font Awesome icons
- Environment variables for Firebase config

---

## Getting started

```bash
# Clone the repo
git clone https://github.com/greshchuk-dev/road-wallet

# Set up environment variables
cp .env.example .env
# Add your Firebase database URL to .env

# Open index.html in your browser
# (or use Live Server in VS Code)
```

---

## Environment variables

Create a `.env` file with:
VITE_ROAD_WALLET_DB=your_firebase_database_url_here

Get this from your Firebase console → Project settings → 
Realtime Database URL.

---

## What I learned

Building this taught me how to work with Firebase Realtime
Database — setting up live listeners with onValue, pushing
and removing data, and keeping the UI in sync automatically.
Splitting costs dynamically across a changing list of
travellers was an interesting state management challenge.

---

## Author

Iryna Greshchuk · [GitHub](https://github.com/greshchuk-dev) ·
[LinkedIn](https://linkedin.com/in/iryna-greshchuk-3a9807337)

