![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![Responsive](https://img.shields.io/badge/Responsive-Design-green)

<br>

<h1 align="center">🎄 Twinsi Christmas 2025 
Advent Calendar Website</h1>

<p align="center">
A festive, interactive calendar built with vanilla JavaScript, HTML, and CSS — featuring 24 boxes, one for each day in December leading up to Christmas.
</p>

<p align="center">
  <a href="https://github.com/VTwin90">
    <img src="https://img.shields.io/github/followers/VTwin90?label=follow&style=social" alt="GitHub followers" />
  </a>
  <a href="https://www.linkedin.com/in/vanja-torp/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>


## ✨ Features

- 🎁 Clickable calendar boxes for each day in December, each with a gift
- 🎉 Confetti animation when opening new gifts
- 🐻 Custom bear mascot in each box
- ⚙️ Adaptive performance mode for low-end devices
- 🌌 Custom animated background with HTML & CSS


<br>

## 🎁 What's Inside?

Each day unlocks a unique surprise — it could be music, a video, a game, a card, or something festive you didn’t expect. The fun is in discovering it!

> No spoilers here — open the boxes to reveal the magic ✨

<br>

## 🛠️ Customize Your Gifts

Want to personalize the surprises? You can edit `data.js` to add your own links to music, videos, games, images, or downloads — but we recommend keeping it secret until reveal day!

```js
export const gifts = [
  { type: 'music', url: 'https://...' },
  { type: 'video', url: 'https://...' },
  { type: 'game', url: 'https://...' },
  { type: 'image', url: 'images/....jpg' },
  { type: 'download', url: 'cards/....png' },
];
```

<br>

## 📱 Device Notes

> ⚠️ On older mobile devices (like iPhone 6s), performance may be slower. For best experience, use a desktop browser or newer phone.

<br>

### 🧭 Favicon & Manifest Notes

I used [RealFaviconGenerator](https://realfavicongenerator.net/) to generate the favicon set and [their checker](https://realfavicongenerator.net/favicon-checker) to validate it.

 > ⚠️ The favicon checker may report missing icons (e.g. `192x192`, `512x512`) when hosted on GitHub Pages due to subpath hosting (`/twinsi-christmas-2025/`). These are false negatives — all icons are correctly linked and verified via Chrome DevTools and direct access.

<br>

## 🚀 Getting Started

To run locally:

```bash
git clone https://github.com/your-username/twinsi-christmas-2025.git
cd twinsi-christmas-2025
open index.html
```

<br>

<p align="center">
    🙌 Credits
    Built by Vanja with holiday spirit ✨
</p>

<p align="center">
  <em>Thanks for strolling through my work.</em><br><br>
  <img src="https://media3.giphy.com/media/6n0N3SFB0XGoD9txBB/giphy.gif" alt="Happy Dog" width="200"/>
</p>