# TicTacToe Deluxe

**TikTakFoe** is an enhanced version of the classic Tic Tac Toe game with innovative gameplay mechanics that add strategic depth and excitement to the traditional puzzle.

🎮 **[Play the Game Here](https://m3koenig.github.io/TikTakFoe/)**

## Features

### Core Gameplay Mechanics

- **🎯 Place** – Classic move: place your piece on an empty cell
- **🔄 Push** – Strategic move: push an opponent's piece to an adjacent cell (chain reaction included!)
- **➡️ Move** – Tactical move: move your own piece to an adjacent empty cell
- **🚫 Block** – Special phase: freeze cells permanently during the growth phase

### Dynamic Board Growth

The board dynamically grows from **3×3 to 5×5** after the first 4 total moves across both players. This growth phase introduces a new layer of strategy and prevents early-game stalemates.

### Blocking Phase

After the board grows, each player gets to block one cell of their choice, preventing either player from placing pieces there. This adds a defensive element to strategic planning.

### Score Tracking

The game tracks wins across multiple matches in your current session. Reset individual matches or all scores as needed.

## How to Play

1. **Player A (✕)** and **Player B (◯)** take turns
2. Choose an action mode:
   - **Setzen (Place):** Place your piece on an empty cell
   - **Schieben (Push):** Push an opponent's piece in any direction (only if your piece is adjacent)
   - **Bewegen (Move):** Move your own piece to an adjacent empty cell
3. **Win Condition:** Get three of your pieces in a row (horizontal, vertical, or diagonal)
4. After the board grows to 5×5, each player blocks one cell
5. Continue playing until someone wins!

## Game Rules

- **Placement & Movement:** Standard chess-like adjacency rules apply
- **Push Mechanics:** When pushing, pieces chain-react down the line until reaching an empty cell. Invalid moves (hitting edges or blocked cells with no landing space) are rejected
- **Blocked Cells:** Cannot be occupied by any piece but can block push chains
- **Win Detection:** Three pieces in a line wins immediately, regardless of board size

## Technologies Used

- **HTML5** – Semantic markup and structure
- **CSS3** – Modern styling with CSS variables and animations
- **Vanilla JavaScript** – Pure logic with no external dependencies (except Google Fonts)
- **PWA Support** – Service Worker for offline-first experience (on HTTPS only)

## Fonts

- **Space Grotesk** – Bold, modern UI typography
- **IBM Plex Mono** – Technical, readable body font

## Browser Compatibility

Works on all modern browsers supporting ES6 JavaScript. Optimized for mobile and desktop viewing.

## Game Design Notes

The mechanics were designed to balance simplicity with strategic depth:
- The growing board prevents early patterns from dominating
- Push mechanics introduce risk/reward decision-making
- The blocking phase adds defensive planning
- Move action provides flexibility without breaking balance

## License

This project is licensed under the **MIT License** – see [LICENSE](LICENSE) file for details.

---

### Quick Links

- 🎮 **[Play Online](https://m3koenig.github.io/TikTakFoe/)**
- 📁 **[Repository](https://github.com/m3koenig/TikTakFoe)**
- 📝 **[MIT License](LICENSE)**

Enjoy the game! 🎉
