# 🎂 A Birthday Surprise 💗

A personalized, interactive 5-page Birthday Progressive Web App (PWA) with music, memory gallery, gaming highlights, personal letter, and interactive birthday cake candle blowing.

---

## ✨ Features
- **Page 1: Birthday Welcome** – Animated greeting card with floating hearts and interactive surprise opener.
- **Page 2: Photo Memories** – Elegant gallery with responsive cards, smooth reveal animations, and personal moments.
- **Page 3: Gaming Memories** – Highlights and shared moments from matches with custom captions.
- **Page 4: Birthday Letter** – Heartfelt letter and warm birthday wishes.
- **Page 5: Make a Wish & Cake** – Interactive candle-blowing experience with celebratory confetti.
- **Background Music Player** – Built-in audio controls with streaming range support.
- **Full PWA Support** – Offline caching via service worker (`sw.js`) and installable on Android, iOS, tablets, and desktop.

---

## 🚀 How to Run Locally

### Requirements
- [Node.js](https://nodejs.org/) (v16 or higher)

### Start the Local Server
```bash
# Using npm
npm start

# Or directly with Node.js
node server.js
```

Then open your browser at:
- **Local:** `http://localhost:8080/`
- **Network (Mobile preview):** `http://<your-local-ip>:8080/`

---

## 🌐 Deploy to GitHub Pages / Vercel / Netlify

### Option 1: GitHub Pages
1. Push this repository to GitHub.
2. In your GitHub repository, go to **Settings > Pages**.
3. Under **Build and deployment > Source**, select **Deploy from a branch**.
4. Choose the `main` branch and `/site` folder (or deploy the repository root using GitHub Actions).

### Option 2: Netlify
1. Drag and drop the `site` folder directly into [Netlify Drop](https://app.netlify.com/drop), or link this GitHub repo.
2. Set Publish directory to: `site`.

### Option 3: Vercel
1. Run `npx vercel` or import this repository on [Vercel](https://vercel.com).
2. Set the root directory to `site`.
