# Snake-3310
Nokia 3310 Snake Clone. Single-file HTML5 game. Zero dependencies. Mobile-first logic with LocalStorage persistence.



# 🐍 Nokia Snake (HTML5 Port)

A lightweight, zero-dependency clone of the classic Nokia 3310 Snake game, written in a single HTML file. Designed for mobile browsers with touch controls and persistent high scores.

## ⚡ Features

* **Monolithic Architecture**: Entire game (Logic, UI, CSS) contained in one `index.html` file (~4KB).
* **Mobile First**: Custom Virtual D-Pad using `ontouchstart` for zero-latency input.
* **Persistent Data**: Uses `localStorage` to save High Scores locally on the device.
* **Retro Aesthetics**: CSS-only styling mimicking the Nokia 3310 LCD palette (#c7f0d8).
* **Responsive**: Viewport hacks to prevent zooming and scrolling during gameplay.

## 🕹️ Live Demo

Play it here: https://dad-89.github.io/Snake-3310/


## 🛠️ Tech Stack

* **Core**: Vanilla JavaScript (ES6)
* **Rendering**: HTML5 `<canvas>`
* **Input**: Touch Events (Mobile) + Keyboard (Desktop fallback)
* **Storage**: Browser LocalStorage API

## 🚀 Deployment

This project is deployed via **GitHub Pages**.
No build steps required. Just push `index.html` to the `main` branch.

---
*Project created for educational purposes. Minimalist coding challenge.*
