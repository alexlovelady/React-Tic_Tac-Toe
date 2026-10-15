# Tic-Tac-Toe in React

A two-player tic-tac-toe game built with Next.js and React, following the classic "time travel" design: every move is stored in history, so you can jump back to any earlier point in the game and continue from there.

## Features

- Alternating X and O turns, with the next player shown
- Winner detection across all eight winning lines
- Move history with "Go to move #N" buttons to rewind and replay

## Run it

```bash
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000).

## Stack

Next.js 14 (App Router), React 18, Tailwind CSS. State lives in React hooks (`useState`), and the game logic is in `src/app/page.js`.

The structure follows the official React tutorial game, built to practice state and component composition.
