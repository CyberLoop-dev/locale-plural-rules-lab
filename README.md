<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:0891b2&height=180&section=header&text=Locale%20Plural%20Rules%20Lab&fontColor=ffffff&fontSize=34" alt="Locale Plural Rules Lab banner"/>
  <br/><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2600&pause=700&center=true&vCenter=true&width=650&lines=Explore+Intl.PluralRules;Compare+cardinal+and+ordinal+forms;Test+numbers+across+locales" alt="Animated title"/>
  <br/><img src="https://img.shields.io/github/license/CyberLoop-dev/locale-plural-rules-lab" alt="License"/> <img src="https://img.shields.io/github/languages/top/CyberLoop-dev/locale-plural-rules-lab" alt="Language"/> <img src="https://img.shields.io/github/stars/CyberLoop-dev/locale-plural-rules-lab" alt="Stars"/> <img src="https://img.shields.io/github/last-commit/CyberLoop-dev/locale-plural-rules-lab" alt="Last commit"/>
  <br/><img src="assets/mark.svg" width="210" alt="Plural category illustration"/>
</p>

## 🧭 Overview

Locale Plural Rules Lab is a browser-based explorer for the built-in `Intl.PluralRules` API. Compare cardinal and ordinal categories, test custom numbers, and inspect how locale rules differ.

## ✨ Features

- 🌍 Try any locale tag supported by the browser's internationalization data.
- 🔢 Switch between cardinal and ordinal selection.
- 🧪 Test custom numeric values and a useful sample range.
- 🏷️ See the locale's resolved plural categories.
- 🔒 All processing stays in the browser; no external libraries.

## 🎬 Demo

Run locally, enter a locale such as `en`, `ar`, or `ru`, and compare the category table. Results depend on the browser's ICU/CLDR data; no hosted demo is claimed.

## 🚀 Quick Start

Requires Node.js 18 or newer.

```bash
npm start
```

Open http://localhost:4173.

## 🧰 Tech Stack

- 🟢 Node.js built-in HTTP server
- 🌐 HTML, CSS, browser JavaScript, and `Intl.PluralRules`
- 📦 No third-party runtime dependencies

## 🗂️ Folder Structure

```text
locale-plural-rules-lab/
├── assets/mark.svg
├── app.js
├── index.html
├── server.js
├── package.json
├── README.md
├── LICENSE
└── .gitignore
```

## 🛣️ Roadmap

- [ ] Add sample phrase templates for each category.
- [ ] Compare multiple locales side by side.
- [ ] Add a small ICU MessageFormat preview.

## 🤝 Contributing

Contributions should include locale examples and explain the browser support assumptions. Test with `npm start` and at least two locales.

## 📄 License

MIT licensed. See [LICENSE](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0891b2,100:111827&height=105&section=footer" alt="Wave footer"/></p>
