# 🧩 Meeple Score

A lightweight, touch-friendly score tracker for **Carcassonne** and other tabletop games.

Designed to run smoothly on an iPad, Meeple Score replaces the physical scoring track when your game goes beyond the board's score limit — especially useful when playing with expansions.

> **Live app:** https://leowpailoei.github.io/meeple-score/

## ✨ Features

- 👥 Supports **2–6 players**
- 🎨 Custom player names and colors
- ➕ Quick score buttons: **+1 through +10**; repeated taps accumulate into one pending score before confirmation
- 🔢 Add any custom score (negative values are still available for corrections)
- ↩️ Undo the latest score change
- 🏰 Detailed scoring categories: **City, Road, Church, Farmer, and Goods**
- 🎁 Goods picker with separate **Chicken, Cloth, and Rice** entries
- 📊 Per-player score breakdown by category and goods type
- 🕘 Score history with scoring category
- 💾 Automatic saving with `localStorage`
- 📱 Compact, responsive dashboard for **2–6 players**, optimized for iPad
- 🏠 Installable with **Add to Home Screen**
- 🌐 Works offline after the first successful load
- 🚫 No account, database, or server required

## 🎯 Why Meeple Score?

Carcassonne's physical score track works well for the base game, but scores can quickly exceed its limit when expansions are added.

Meeple Score is designed to sit beside the board during a game:

1. Open the app on an iPad or tablet
2. Set up the players
3. Tap whenever someone earns points
4. Keep playing — there is no practical score limit

Your current game is saved automatically in the browser, so refreshing or reopening the page does not immediately reset the score.

## 📱 Install on iPad

Open the live app in **Safari**:

https://leowpailoei.github.io/meeple-score/

Then choose:

**Share → Add to Home Screen**

Meeple Score can then be launched from the Home Screen like an app.

## 💾 How data is stored

Meeple Score currently uses browser `localStorage`.

That means:

- Scores are stored on the device/browser you are using
- No player data is uploaded to GitHub
- No sign-in is required
- Different devices do not automatically sync with each other
- Clearing browser website data may remove saved game data

## 🛠️ Built With

- HTML
- CSS
- JavaScript
- Progressive Web App (PWA)
- Service Worker
- GitHub Pages

## 💻 Run Locally

Because the PWA and Service Worker require HTTP/HTTPS, run the project through a local web server instead of opening `index.html` directly.

If Python is installed:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 🚀 Deployment

This project is deployed for free with **GitHub Pages** from the `main` branch.

Any future update committed to the deployment branch can be published to the same website URL.

## 🗺️ Possible Future Improvements

- Expansion modifiers/tags such as Inn, Cathedral, Pig, and Big Meeple
- Enhanced end-of-game summary
- Per-player statistics
- Multiple saved games
- Improved game history
- More customization options
- Optional synchronization between devices

---

Made for easier scoring around the Carcassonne table. 🏰
