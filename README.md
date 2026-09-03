[![Developed & Maintained by CaptainEXE](https://img.shields.io/badge/Developed%20%26%20Maintained%20by-CaptainEXE-00FFFF?style=for-the-badge&labelColor=0e1117&logo=reactivex&logoColor=white)](https://thecaptainexe.vercel.app/)
---
# TypeEXE

A clean, responsive, and minimal typing test built with vanilla HTML, CSS, and JavaScript. Designed for speed, precision, and an aesthetic typing experience inspired by modern color palettes.

![License](https://img.shields.io/badge/license-MIT-purple.svg)
![Tech Stack](https://img.shields.io/badge/tech-HTML5%20%7C%20CSS3%20%7C%20JS-blue.svg)

## 🌐 Quick Links

- **Live Demo (GitHub Pages):** [https://thecaptainexe.github.io/Type-EXE/](https://thecaptainexe.github.io/Type-EXE/)
- **Latest Version / Downloads:** Get stable releases and update history on the [Versions Page](https://github.com/thecaptainexe/Type-EXE/releases).

## ✨ Features

- **Multiple Test Modes:**
  - **Time:** Test your speed against fixed time limits (5s, 15s, 30s).
  - **Quote:** Type randomly selected short quotes.
  - **Zen:** Infinite typing mode without time pressure. Press `` ` `` anytime to finish and view stats.
- **Dynamic Caret Fitting:** Caret size and position dynamically adjust to match exact letter line-heights and font sizes across devices.
- **Real-Time WPM Analytics:** Visual WPM speed graph generated via **Chart.js** after every test run, including Zen and Quote modes.
- **Catppuccin Color Themes:** Built-in theme selector featuring `Mocha`, `Macchiato`, `Frappé`, and `Latte`.
- **Full Screen Lockdown:** Responsive, scrollbar-free layout optimized for both mobile and desktop screens.
- **Modifiers:** Toggle numbers and punctuation for extra typing challenges.

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Charts:** [Chart.js](https://www.chartjs.org/)
- **Typography:** [Fira Code](https://fonts.google.com/specimen/Fira+Code) via Google Fonts

## 🚀 Getting Started

### Option 1: Web Version (GitHub Pages)
Play instantly in your browser without downloading anything by visiting the [GitHub Pages Deployment](https://thecaptainexe.github.io/Type-EXE/).

### Option 2: Download the Latest Version
To grab a standalone zip of the latest tagged version, head over to the [Releases / Versions Page](https://github.com/thecaptainexe/Type-EXE/releases) and download the latest asset package.

### Option 3: Clone the Repository
Clone the repository locally to edit or host it yourself:

1. Clone the repository:
   ```bash
   git clone [https://github.com/thecaptainexe/Type-EXE.git](https://github.com/thecaptainexe/Type-EXE.git)
   ```
2. Navigate to the project directory:
   ```bash
   cd Type-EXE
   ```
3. Open `index.html` in your favorite web browser.

## 🎨 Theme Customization

Themes are controlled via CSS custom properties in `style.css`. You can add new color palettes by defining new CSS rules on the `body` element:

```css
body.theme-custom {
    --bg: #1e1e2e;
    --main: #cba6f7; 
    --caret: #cba6f7;
    --sub: #6c7086;
    --text: #cdd6f4;
    --error: #f38ba8;
    --error-extra: #eba0ac;
}
```

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Developed by <a href="https://thecaptainexe.vercel.app">CaptainEXE</a>
</p>
