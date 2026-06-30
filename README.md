# 2048 Game

A browser implementation of the classic **2048** puzzle game. Combine tiles with
the same numbers using the arrow keys to merge them and reach the **2048** tile.
The game tracks your score, detects win and lose states, and lets you start over
at any time.

## Live Preview

[Play the game](https://redfield-mp.github.io/game-2048/)

## Technologies Used

- **HTML5** — semantic markup of the game board
- **SCSS (Sass)** — styling and tile theming
- **JavaScript (ES2022)** — game logic built with an OOP `Game` class
- **Parcel** — bundling and the local dev server
- **ESLint**, **Stylelint**, **Prettier** — code quality and formatting
- **Cypress** — end-to-end tests

## Getting Started

Clone the repository:

```bash
git clone https://github.com/redfield-mp/game-2048.git
cd game-2048
```

Install dependencies:

```bash
npm install
```

Run the project locally:

```bash
npm start
```

The app will be available at the URL printed by Parcel (usually
`http://localhost:1234`).

Run the tests:

```bash
npm test
```

## Features

- Tile movement and merging in all four directions with the arrow keys
- Live score that increases with every merge
- Win detection when the **2048** tile is reached
- Lose detection when no moves are left
- Start / Restart control to begin a new game at any time
