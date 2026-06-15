# 🎮 Game 2048

A classic puzzle game where the goal is to combine tiles and reach the number **2048**.  
This project demonstrates game logic implementation in JavaScript and a simple UI.

---


## 🔗 Live Preview
[Play the Game](https://EStasyuk.github.io/game_2048/)

---

## 🎨 Design Reference
This project is based on the original design of the 2048 game.  
(https://play2048.co/)

---

Classic 2048 puzzle game implemented with JavaScript.

## 📏 Rules
1. The game field is **4 x 4**.
2. Each cell can be empty or contain one of the numbers: `2, 4, 8 ... 2^n`.
3. The player can move cells using **keyboard arrows**.
4. All numbers move in the selected direction until all empty cells are filled:
   - Two equal cells merge into a doubled number.
   - A merged cell cannot be merged twice during one move.
5. A move is possible only if at least one cell changes.
6. After each move, `2` or `4` appears in a random empty cell (`4` has 10% probability).
7. When `2048` appears in any cell, a **win message** is shown.
8. If no moves are available, a **game over message** is shown.
9. Hide the start message when the game begins.
10. Change the **Start** button to **Restart** after the first move.
11. The **Restart** button resets the game to the initial state.
12. The score increases with each move by the sum of all merged cells.

## 🛠 Technologies Used
- **HTML5** — game UI
- **CSS3** — styling
- **JavaScript (ES6+)** — game logic
- **Modules** — structured code (`Game.class.js`)

---

## 🚀 Getting Started

To run the project locally:

### 1. Clone the repository
```bash
git clone https://github.com/EStasyuk/game_2048.git
cd game_2048

Install dependencies
bash
npm install

Run the project locally
bash
npm start