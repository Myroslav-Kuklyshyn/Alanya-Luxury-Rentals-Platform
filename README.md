# 🌴 Alanya Luxury Rentals Platform

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Web-000000?style=for-the-badge&logo=flask&logoColor=white)
![Telegram API](https://img.shields.io/badge/Telegram_Bot-Admin_Panel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

A commercial full-stack web platform for renting luxury apartments in Alanya, Turkey. The system features a **dynamic Content Management System (CMS) built directly into a Telegram Bot**, allowing the owner to manage prices, reviews, and bookings in real-time from their smartphone.

---

## 🔴 Live Demo
The project is deployed and fully functional:
### [🌍 Visit Website (alanya-apartaments.com)](https://alanya-apartaments.com)

---

## 🚀 Key Features

### 🌐 Frontend (Multi-language & Interactive)
* **5 Language Support:** Fully localized for EN, UA, TR, CZ, RU audiences.
* **Modern UX/UI:** Cinematic video backgrounds, smooth scroll animations (`IntersectionObserver`), and glassmorphism design.
* **Dynamic Data:** Prices and reviews are fetched asynchronously via REST API endpoints (`/api/prices`) without page reloads.

### 🤖 Telegram Admin Bot (The "Brain")
Instead of a complex web admin panel, this project uses a Telegram Bot for instant management:
* **Real-time Price Updates:** Change rental rates for any apartment instantly via bot buttons.
* **Review Moderation:** Receive new reviews from the site directly to the bot and approve/delete them.
* **Admin Management:** Securely add or remove other managers via chat commands.
* **Contact Updates:** Change the contact phone number displayed on the site on the fly.

### ⚙️ Backend Architecture
* **Server:** Flask (Python) handles HTTP requests, API routes, and serves static files.
* **Database:** SQLite stores apartment data, user reviews, prices, and admin logs.
* **API:** Custom JSON endpoints connect the frontend JS with the backend database.

---

## 🛠️ Tech Stack

| Component | Technology | Description |
|-----------|------------|-------------|
| **Core** | Python 3 | Backend logic |
| **Web Framework** | Flask | API & Routing |
| **Bot Library** | pyTelegramBotAPI | Async interaction with Telegram |
| **Frontend** | HTML5, CSS3, JS | Vanilla JS, CSS Animations, Responsive Design |
| **Database** | SQLite | Lightweight data storage |

---
