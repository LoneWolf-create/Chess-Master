♤Chess Master♤

Chess Master is a fully responsive, modern web-based chess application designed for seamless play on both mobile devices and desktop computers. Built entirely as a self-contained single-file web app, it combines high-performance client-side logic with a sleek Tailwind CSS interface.

■Features

Players can choose between a single-player match against an artificial intelligence opponent or a local two-player pass-and-play experience. When playing against the computer, users can select their preferred side as either White or Black and choose among Easy, Medium, or Hard difficulty settings.
The artificial intelligence is powered by a minimax algorithm equipped with alpha-beta pruning, quiescence search, piece-square tables, and move ordering heuristics. For enhanced gameplay, the engine integrates with the Lichess Opening Explorer API to pull standard opening book moves dynamically, backed by a robust fallback timeout system to ensure smooth offline performance.
The application includes multiple board themes such as Classic Wood, Emerald Green, Slate Gray, and Ocean Blue. It also features customizable board flipping, move history tracking with clickable navigation, captured pieces indicators, and immersive sound effects synthesized via the Web Audio API for moves, captures, checks, and game over conditions.
After or during a match, players can enter a comprehensive review and replay mode. The replay toolbar allows users to jump to the start, step backward or forward through individual moves, auto-play the entire game sequence, or instantly resume active play.

■Technical Architecture

The project is structured as a single-file HTML5 document containing all markup, responsive styling, and application logic. Styling and layout are handled by Tailwind CSS via CDN alongside FontAwesome for interface iconography. Chess rule validation, legal move generation, and game state management are driven by the stable chess.js library. Additionally, sound effects are generated programmatically using a custom Web Audio API synthesizer that requires no external audio files.

■Getting Started

To run Chess Master locally or deploy it to GitHub Pages, simply download or clone the repository and open the Chess Master.html file in any modern web browser. No build steps, package managers, or server installations are required.
On desktop systems, users can utilize keyboard shortcuts such as the Left and Right arrow keys for replay navigation, Escape to clear selections or close modals, and Ctrl+Z or Cmd+Z to undo moves.
