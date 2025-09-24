# Crypto & Stock Market Web App

A Flask-based web application that allows users to track cryptocurrencies and stocks in real-time, manage their personalized watchlists, and view market insights. The app integrates with the Binance API for live data and uses a database for user management.

---

## 🚀 Features
- User authentication (Sign up / Login)
- Real-time cryptocurrency & stock data from Binance API
- Personalized watchlist management
- Responsive UI with Flask templates
- Static assets (CSS, images) for a clean design

---

## 📂 Project Structure
Crypto_db/
│── app.py # Main Flask app entry point
---
│── backend.py # Backend logic (DB operations, watchlist, etc.)
---
│── binancedata.py # Binance API integration
---
│── static/ # CSS styles & images
---
│── templates/ # HTML templates (login, signup, home, market, etc.)
---
│── .vscode/ # Editor settings

---

## 🛠️ Tech Stack
- **Backend:** Python (Flask)
- **Database:** MongoDB / MySQL (depending on configuration)
- **API:** Binance API
- **Frontend:** HTML, CSS (Flask templates, static assets)

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Arehan19/Crypto-and-Stock-Market-App.git
   cd crypto-stock-app
