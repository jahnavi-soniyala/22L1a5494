# 🔗 URL Shortener Web App

A simple **React-based URL Shortener** with statistics, built using **Material UI** and **LocalStorage**.  
This project allows users to shorten URLs, set expiry times, use custom shortcodes, and view analytics for each shortened link.

---

## 🚀 Features
- Shorten URLs with:
  - Custom shortcode (optional).
  - Validity period (default 30 minutes).
- Redirect from shortened URLs (with expiry check).
- View statistics:
  - Creation & expiry time.
  - Total clicks.
  - Click details (timestamp, source, location).
- Client-side validation and error handling.
- Persistent data storage using **LocalStorage**.
- Clean UI with **Material UI**.

---

## 🛠️ Tech Stack
- **React** (Frontend)
- **React Router DOM** (Routing)
- **Material UI** (UI Components)
- **LocalStorage** (Data Persistence)

---

## 📂 Project Structure
  ### name: "URL Shortener Web App"
  description: >
    A simple React-based URL Shortener with statistics, built using Material UI and LocalStorage.
    Allows users to shorten URLs, set expiry times, use custom shortcodes, and view analytics.

#### structure:
  src:
    - App.js
    - index.js
  utils:
    - storage.js
  pages:
    - ShortenerPage.js
    - RedirectPage.js
    - StatsPage.js

#### setup:
  steps:
    - "Clone the repo:"
    - |
      git clone https://github.com/jahnavi-soniyala/22L1a5494.git
      cd 22L1a5494
    - "Install dependencies:"
    - "npm install"
    - "Run the app:"
    - "npm start"
    - "Open in browser:"
    - "http://localhost:3000"

#### usage:
  - "Go to `/` → Shorten URLs."
  - "Go to `/stats` → View statistics."
  - "Visit `/shortcode` → Redirect to original URL (if valid & not expired)."

#### example:
  shorten: "https://example.com → http://localhost:3000/abc12"
  stats_page:
    - "Short URL"
    - "Original URL"
    - "Expiry Date"
    - "Click Count & Details"

#### constraints:
  - "Only Material UI allowed (no Tailwind/ShadCN)."
  - "Must run on http://localhost:3000."
  - "Client-side input validation."
  - "Graceful error handling."
  - "Clean and simple UI."

#### future_improvements:
  - "Backend integration (Node/Express + DB)."
  - "Real geo-location tracking for clicks."
  - "User authentication to save history."

