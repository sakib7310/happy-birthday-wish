<div align="center">

# 🎁 Secret Birthday Gift

<p align="center">
  <strong>An interactive, beautifully animated Shinchan-themed birthday surprise web application designed with pure HTML, CSS, and Vanilla JavaScript.</strong>
</p>

[![Vercel](https://img.shields.io/badge/Vercel-Live%20Demo-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://secret-birthday-gift-iota.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Desktop-ff69b4?style=for-the-badge)

<p align="center">
  <a href="https://secret-birthday-gift-iota.vercel.app"><strong>🌐 Live Demo</strong></a> •
  <a href="#-features">Features</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-how-to-customize">Customization</a> •
  <a href="#-project-structure">Structure</a> •
  <a href="#-keyboard-shortcuts">Shortcuts</a> •
  <a href="#-license">License</a>
</p>

---

</div>

## ✨ Overview

**Secret Birthday Gift** is a heartfelt digital birthday experience built to create an unforgettable midnight surprise. It takes the viewer through an interactive journey featuring theatrical velvet stage curtains, a Shinchan-style secret lockscreen, playful teaser interactions, and three unlocked mystery gifts.

Everything runs smoothly on desktop, tablet, and mobile browsers with **zero external frameworks or heavy dependencies** — just pure vanilla web technologies.

---

## 🌟 Interactive Journey & Features

### 1. 🕛 The Midnight Countdown & Grand Reveal
- **Analog & Digital Stage Clock**: Accurate ticking clock face counting down the final 5 seconds to midnight (`12:00:00 AM`).
- **Theatrical Velvet Curtains**: Split-opening red velvet stage curtains with light burst effects revealing the secret verification screen.
- **Warm Ambient Effects**: Floating golden candlelight motes, falling rose petals, and interactive cursor sparkle hearts.

### 2. 🔐 Shinchan Secret Passcode Screen
- **Cameo Portrait**: Cameo frame starring Shinchan with dynamic expressive reactions.
- **4-Digit Secret PIN Entry**: Interactive circular phone-style dial pad and full physical keyboard support.
- **Playful Error Handling**: Custom Shinchan reaction expressions with gentle card shake animations for incorrect passcodes.

### 3. 💖 Interactive Teaser Transition
- **Dynamic Curved SVG Typography**: Fluid arched headers that react and bounce.
- **Shinchan Reactions**: Dynamic dancing GIFs that change if the user hesitates between "YES" and "NO".

### 4. 🎁 3 Floating Mystery Gift Boxes
Once unlocked, users are greeted by three floating neon-accented heart gift boxes:

- **📸 Box 1: Hanging Polaroid Clothesline Gallery**
  - Aesthetic wooden clothesline with mini wooden clothespins.
  - Real photo frames with gentle sway physics when clicked or tapped.
  - Smooth horizontal scroll controls (buttons and left/right keyboard arrows).

- **🎂 Box 2: Interactive Birthday Cake & Make A Wish**
  - Hand-crafted 2-tier pastel birthday cake topped with 7 flickering candle flames.
  - Click/tap each candle to blow it out individually, or press `Space`/`Enter` to extinguish all at once.
  - Triggers a celebratory confetti explosion and reveals a birthday banner.

- **💌 Box 3: 3D Perspective Polaroid & Live Typewriter Letter**
  - 3D tilted Polaroid photo adorned with an ornate purple ribbon bow.
  - Real-time emotional typewriter animation typing out the heartfelt birthday message line-by-line.
  - Click-to-reveal instant skip option for quick reading.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic elements, SVG vector illustrations, and responsive layout containers.
- **CSS3**: Custom keyframe animations, glassmorphism, flexbox/grid architecture, responsive media queries, and vintage gingham patterns.
- **Vanilla JavaScript (ES6+)**: Event listeners, dynamic DOM manipulation, math-based particle systems, and keyboard navigation.

---

## 📂 Project Structure

```text
Secret-Birthday-Gift/
│
├── assets/                       # Image assets and animated GIFs
│   ├── memory1.jpg               # Polaroid memory photo 1
│   ├── memory2.jpg               # Polaroid memory photo 2
│   ├── memory3.jpg               # Polaroid memory photo 3
│   ├── memory4.jpg               # Polaroid memory photo 4
│   ├── memory5.jpg               # Polaroid memory photo 5
│   ├── shinchan-birthday.png     # Cameo lockscreen mascot
│   ├── shinchan-dance.gif        # Dancing Shinchan celebration
│   ├── shinchan-excited.gif      # Excited reaction GIF
│   ├── shinchan-gift.gif         # Gift box mascot
│   ├── shinchan-pleading.gif     # Pleading Shinchan when 'No' is clicked
│   └── shinchan-wrong.png        # Wrong passcode reaction
│
├── .gitignore                    # Git ignore file for clean commits
├── index.html                    # Main HTML application markup
├── LICENSE                       # MIT License
├── README.md                     # Documentation
├── script.js                     # Interaction logic, animations & state handling
└── style.css                     # Complete design system & custom animations
```

---

## 🚀 Quick Start

### 🌐 Live Production Demo
Experience the surprise live: **[https://secret-birthday-gift-iota.vercel.app](https://secret-birthday-gift-iota.vercel.app)**

No build tools, bundlers, or package installations needed!

### Running Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/saklincodes/Secret-Birthday-Gift.git
   ```

2. **Navigate into the project directory:**
   ```bash
   cd Secret-Birthday-Gift
   ```

3. **Open in browser:**
   - Double-click `index.html` to open directly in any modern browser (Chrome, Edge, Firefox, Safari).
   - *Or* launch with VS Code's **Live Server** extension for live-reload during customization.

### 🌐 Deploying to GitHub Pages (Optional)

You can easily host this for free on GitHub Pages to share via link:
1. Go to your repository on GitHub: `https://github.com/saklincodes/Secret-Birthday-Gift`
2. Navigate to **Settings** > **Pages**.
3. Under **Branch**, select `main` (or `master`) branch and folder `/ (root)`.
4. Click **Save** — within 1–2 minutes, your surprise will be live at:
   `https://saklincodes.github.io/Secret-Birthday-Gift/`

---

## ⚙️ How to Customize for Someone Special

You can personalize this surprise for your loved one in just a few minutes:

### 1. Change the 4-Digit Passcode
Open `script.js` and locate line 62:
```javascript
const TARGET_PASSCODE = "2005"; // Set your desired 4-digit code (e.g., birth year or special date)
```

### 2. Replace Memory Photos
Replace the image files inside the `assets/` directory with your own photos, keeping the same filenames:
- `assets/memory1.jpg` through `assets/memory5.jpg`

### 3. Edit the Birthday Letter Text
Open `script.js` and edit the `LETTER_SECTIONS` array (around line 467):
```javascript
const LETTER_SECTIONS = [
  {
    id: 'letter-headline-el',
    text: "Happy birthday to my favourite\nperson! ❤️"
  },
  {
    id: 'letter-p1-el',
    text: "Your custom sweet message here..."
  },
  {
    id: 'letter-p2-el',
    text: "Another paragraph sharing your feelings..."
  },
  {
    id: 'letter-closing-el',
    text: "Happy birthday, my love. I love you more than you know. 🫶🏻🎂❤️"
  }
];
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| `0` – `9` | Type passcode digits on the lockscreen |
| `Backspace` | Delete last entered passcode digit |
| `Enter` | Submit passcode / Extinguish all cake candles |
| `Space` | Extinguish cake candles / Scroll memories right |
| `←` / `→` | Scroll through hanging memory polaroids |
| `Escape` | Close any open modal / Return to gifts |

---

## 📱 Browser Compatibility

- Google Chrome (Latest)
- Microsoft Edge (Latest)
- Mozilla Firefox (Latest)
- Apple Safari (iOS & macOS)
- Opera / Brave

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/saklincodes/Secret-Birthday-Gift/issues) if you want to contribute.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author

Created with 💖 by **[@saklincodes](https://github.com/saklincodes)**

- GitHub: [@saklincodes](https://github.com/saklincodes)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to use and customize it to make someone smile on their special day!
