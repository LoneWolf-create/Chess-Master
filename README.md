# Chess Master ♟️

A feature-rich, high-performance, and responsive single-file chess web application built with HTML5, Tailwind CSS, and `chess.js`. Designed with a modern dark-themed UI, it provides an immersive chess-playing experience optimized for both mobile and desktop browsers.

[![Play Live](https://img.shields.io/badge/Play%20Live-%E2%99%9F%20Chess%20Master-amber?style=for-the-badge)](https://jeffry-lacanglacang.github.io/Chess-Master/)

---

## 🌟 Key Features

* **Flexible Game Modes**: 
  * **VS AI**: Play against an intelligent computer opponent with customizable difficulty settings (Easy, Medium, Hard).
  * **2 Player**: Local pass-and-play mode for two human players on the same device.
* **Smart AI & Opening Explorer**: 
  * Features a custom Minimax algorithm equipped with alpha-beta pruning, move ordering heuristics, and quiescence search.
  * Integrated with the **Lichess Opening Explorer API** to play realistic opening book moves.
* **Interactive Replay & Analysis Suite**: 
  * Full game review mode with step-by-step navigation (Jump to Start, Step Back, Auto-Play, Step Forward, Jump to End).
  * Interactive move history drawer tracking all moves in Standard Algebraic Notation (SAN).
* **Audio & Visual Customization**: 
  * Built-in Web Audio API synthesizer for immersive sound effects (moves, captures, checks, game over).
  * Multiple board visual themes: Classic Wood, Emerald Green, Slate Gray, and Ocean Blue.
  * Customizable board flipping and side selection (Play as White or Black).
* **Cross-Platform Compatibility**: 
  * Fully responsive touch-friendly layout designed for smartphones, tablets, and desktop displays.
  * Desktop keyboard shortcuts (`Ctrl+Z` to undo, Left/Right arrows for replay, `Esc` to cancel selection).

---

## 🚀 Quick Start & Live Demo

You can play the game instantly without installing anything by visiting the live deployment:
👉 **[https://jeffry-lacanglacang.github.io/Chess-Master/](https://jeffry-lacanglacang.github.io/Chess-Master/)**

### Running Locally
Because Chess Master follows a **Single-File Architecture**, setting up and running the application requires zero complex build steps or dependencies:

1. Clone or download this repository to your local machine:
   ```bash
   git clone https://github.com/jeffry-lacanglacang/Chess-Master.git
   ```
2. Navigate to the folder and open `Chess Master.html` (or your primary HTML file) in any modern web browser (Chrome, Safari, Firefox, Edge).

---

## 🛠️ Technical Architecture

* **Frontend Framework**: Vanilla JavaScript (ES6+) with reactive UI rendering loops.
* **Styling**: Tailwind CSS via CDN for utility-first styling and custom CSS variables for safe-area insets.
* **Chess Logic Engine**: [chess.js (v0.10.3)](https://github.com/jhlywa/chess.js) handling move generation, rule verification, check/mate state detection, FEN parsing, and PGN history.
* **Icons & Fonts**: FontAwesome 6.4.0 and Google Fonts (Inter).

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).