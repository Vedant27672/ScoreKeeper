Deployed : https://score-keeper-webb.netlify.app

ScoreKeeper

A lightweight, responsive score-keeping web app built with HTML and JavaScript. It provides a simple UI for tracking points for two players (or teams), with configurable winning score, increment/reset controls, and persistent settings where applicable.

Tech stack

HTML5 JavaScript (vanilla JS, DOM manipulation, event handling) CSS3 (responsive layout, basic styling)

Basic info

Purpose: Provide a minimal, easy-to-use score tracker you can drop into a game night, classroom activity, or practice session. It demonstrates clean separation of markup, styling, and logic while remaining dependency-free.

Structure: Plain HTML markup for the UI, CSS for layout and styling, and JavaScript to manage score state, controls, and game rules. The project contains an index.html as the main entry point and a script.js file that implements the scoring behavior.

Customization:

Change player names, colors, and button labels directly in the HTML.
Adjust winning score via the UI control or change the default value in the JavaScript.
Modify styles in the CSS to fit your brand or layout preferences.
No build tools or external libraries required.
Usage:

Open index.html in a browser to run the app locally.
Optionally host the files on GitHub Pages or any static-file hosting provider for a public demo.
Quick start

Clone the repo: git clone https://github.com/Vedant27672/ScoreKeeper.git

Open the app:

Open index.html in your browser (e.g., double-click the file or use Live Server).
Basic controls:

Use the + buttons to increment each player's score.
Use the winning score control (select or input) to set the target.
Use Reset to zero both scores and start a new match.
Features

Two-player score tracking with separate increment buttons.
Configurable winning score and end-of-game state (disables further scoring when reached).
Reset button to start a new game quickly.
Small, responsive UI that works on desktop and mobile.
Clear, accessible controls and visual win indication.
File structure (example)

index.html — main HTML file with the UI
styles.css — app styles and responsive rules
script.js — scoring logic and event handlers
README.md — this file

Contact

For questions or contributions, open an issue or submit a pull request in this repository.
