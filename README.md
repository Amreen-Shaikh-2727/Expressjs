# React Chess Game

A responsive local two-player chess game built with React, Vite, `react-chessboard`, and `chess.js`.

## Features

- Interactive chessboard with drag-and-drop and click-to-move
- Legal move validation and highlighted legal moves
- Alternating turns
- Check, checkmate, stalemate, and draw detection
- Ten-minute countdown clock for each player, with an option to turn clocks off
- Move history in standard algebraic notation
- Undo the last move
- Flip the board
- Captured piece display
- Pawn promotion to queen
- Responsive layout for desktop and mobile

## Run locally

1. Install Node.js.
2. Open this folder in a terminal.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL printed in the terminal.

## Build

```bash
npm run build
```

## Notes

This is a local two-player game on one device. It does not include online multiplayer, an AI opponent, or a backend. Pawn promotion currently promotes to a queen automatically.
