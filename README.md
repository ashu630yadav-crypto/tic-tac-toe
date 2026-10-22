# 🎮 Tic Tac Toe — Neon Edition

A sleek, neon-glow **Tic Tac Toe** game built with pure **HTML, CSS, and JavaScript** — zero dependencies, one file, runs anywhere.

**Designed by [Ashutosh Yadav](https://github.com/ashu630yadav-crypto)** 🔥

---

## 🔗 Play Now

> **Live game:** [https://ashu630yadav-crypto.github.io/tic-tac-toe/](https://ashu630yadav-crypto.github.io/tic-tac-toe/)

Or run locally — just open `index.html` in any browser.

## ✨ Features

| Feature | Description |
|---|---|
| 🧑‍🤝‍🧑 **2 Players** | Play hot-seat with a friend on the same device |
| 🤖 **vs Computer** | Human (X) vs Computer (O) |
| 🧠 **3 Difficulty Levels** | Easy (random moves sometimes), Medium (3-move lookahead), Hard (full minimax search — *it fights, and it wins*) |
| 🏆 **Score Tracking** | X wins / O wins / Draws, with a reset button |
| 💡 **Win Highlight** | Winning line glows golden on victory |
| ⌨️ **Keyboard Controls** | `1`–`9` to play a square, `R` for a new game |
| ♿ **Accessible** | ARIA labels, keyboard playable, responsive layout |
| 📱 **Responsive** | Looks great on phones, tablets, and desktops |

## 🕹️ How to Play

1. Pick a mode: **2 Players** or **vs Computer**
2. You play as **X** — click any square (or press its number key)
3. Get **three in a row** — horizontally, vertically, or diagonally — to win
4. Game auto-locks after a win/draw; hit **New Game** to play again

## 🤖 About the AI

The computer opponent uses the **minimax algorithm** with depth-limited search:

- **Easy** — sometimes plays a random open square
- **Medium** — searches 3 moves deep
- **Hard** — full-depth search; it will *never* lose, and it will happily ignore blocking you if it can win first 😈

## 🗂️ Project Structure

```
tic-tac-toe/
└── index.html   # the entire game (HTML + CSS + JS, no dependencies)
```

## 🛠️ Tech Stack

- HTML5
- CSS3 (gradients, glows, animations — no frameworks)
- Vanilla JavaScript (minimax AI, no libraries)

## 📄 License

Free to use, share, and modify — credit is appreciated. 🙌

---

<p align="center"><b>🎮 Designed by Ashutosh Yadav</b></p>
