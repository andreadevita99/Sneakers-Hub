# Sneakers Hub – Sneaker Collection Gallery

A static, responsive web gallery to showcase your sneaker collection, inspired by Notion’s clean design. Built with HTML, CSS, and JavaScript in a single file, it offers a modern browsing experience with dual-language support (Italian/English), dark/light theme, and automatic EU/US shoe size conversion.

## ✨ Features
 - 📱 Fully Responsive – Adapts seamlessly to desktop, tablet, and mobile devices.
 - 🖱️ Smooth Interactions – Subtle hover overlay and image zoom for an elegant feel.
 - 🌓 Dark / Light Mode – iOS‑style toggle with Sun/Moon emojis, persistent via localStorage.
 - 🇮🇹🇬🇧 Multi‑Language Support – Switch between Italian and English with flag buttons; sizes automatically convert between EU and US notation.
 - 🖼️ Dynamic Image Loading – All sneaker images are served via jsDelivr from a public GitHub repository.
 - 📦 Single‑File Architecture – Entire application is contained in one HTML file for easy deployment.

## 🌐 Language & Size Conversion
 - **Italian (default):** Sizes are displayed as N° 40, N° 39-40, etc
 - **English:** The language button switches to English and automatically converts the numeric part of the size to US notation (e.g., N° 40 → N° 7, N° 39-40 → N° 6.5-7).
 - The `N°` prefix remains unchanged in both languages for consistency.

## 📱 Responsive Breakpoints
- **Desktop:** Grid with flexible columns (`minmax(220px, 1fr)`).
- **Tablet & Mobile:** Columns shrink to 150px and 2‑column layout on very small screens.
- All interactive elements (toggle, buttons) are touch‑friendly.

## 🧰 Technologies Used
- **HTML5** – Semantic structure and metadata.
- **CSS3** – Custom properties, Flexbox/Grid, transitions, and responsive design.
- **JavaScript (ES6)** – Dynamic rendering, language switching, theme persistence, and size conversion.
- **jsDelivr CDN** – Serves images and favicon directly from the GitHub repository.
- **GitHub** – Hosting for both the code and static assets.

## Author

[Andrea De Vita](https://github.com/andreadevita99)

## License

All rights reserved. This project is provided for demonstration purposes only. No permission is granted to use, copy, modify, merge, publish, distribute, sublicense, or otherwise reproduce any part of this software without explicit written consent from the author. Unauthorized use, modification, or redistribution is strictly prohibited.
