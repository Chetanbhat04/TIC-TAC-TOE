
# Tic-Tac-Toe Game

A simple **Tic-Tac-Toe** game built using **HTML, CSS, and JavaScript**. The game allows two players to play turn by turn and determines the winner based on predefined win patterns.

## 🎮 Features
- Two-player turn-based gameplay (Player X & Player O).
- Detects and announces the winner.
- Tracks game draws.
- Option to reset the game or start a new game.

## 📌 How to Play
1. Open the game in a browser.
2. Players take turns clicking on empty boxes to mark **"O"** or **"X"**.
3. The game announces the winner when a winning pattern is detected.
4. If all boxes are filled and no winner is found, the game ends in a **draw**.
5. Click **Reset** to clear the board and start again.

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/tic-tac-toe.git
cd tic-tac-toe
```

### 2️⃣ Open `index.html`
Simply open the `index.html` file in your browser to play the game.

## 🛠️ Code Structure
- `index.html` → Structure of the game.
- `style.css` → Styling of the game board and elements.
- `script.js` → Game logic and winner detection.

## 🖥️ JavaScript Logic Breakdown
### 🔹 Variables
```js
let boxes = document.querySelectorAll(".box");
let resetBtn = document.querySelector("#reset-btn");
let newGameBtn = document.querySelector("#new-btn");
let msgContainer = document.querySelector(".msg-container");
let msg = document.querySelector("#msg");
```

### 🔹 Win Patterns
```js
const winPatterns = [
  [0, 1, 2], [0, 3, 6], [0, 4, 8],
  [1, 4, 7], [2, 5, 8], [2, 4, 6],
  [3, 4, 5], [6, 7, 8]
];
```

### 🔹 Game Functions
- **Click Event** → Assigns **"O"** or **"X"** to the clicked box.
- **Check Winner** → Iterates through `winPatterns` to determine the winner.
- **Game Draw** → Checks if all boxes are filled and no winner is found.
- **Reset Game** → Clears the board and restarts the game.

## 🎯 Future Enhancements
- Add a **scoreboard** to track wins.
- Improve UI with **animations**.
- Implement an **AI-based** single-player mode.

## 📜 License
This project is open-source and available under the **MIT License**.

## 💡 Contributing
Feel free to **fork** this repository, create new features, and submit **pull requests**!

## 📧 Contact
For any questions or suggestions, reach out via [GitHub Issues](https://github.com/your-username/tic-tac-toe/issues).

---
🎉 **Enjoy the game and have fun coding!** 🚀

