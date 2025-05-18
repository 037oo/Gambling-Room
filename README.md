# Gambling-Room
# 🎲 Dice Game - PHP Web App

A simple yet fun multiplayer dice game built with **PHP**, **HTML**, **CSS**, and **JavaScript**. Up to three players can compete to roll the highest total score based on the number of dice and throws selected. The game uses PHP sessions to manage scores and user states across rounds.

![image](https://github.com/user-attachments/assets/21195b2a-9442-4f4c-8986-3496b44730c3)


---

## 🚀 Features

- 🎮 3-player turn-based gameplay
- 🎲 Dynamic dice rolls using random number generation
- 🧮 Configurable number of dice and throws
- 🏆 Winner announcement with fireworks effect
- 💾 Session-based state management (no database needed)
- 🌐 Fully client-server interaction with styled front-end

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript, jQuery
- **Backend:** PHP 7+
- **Session Storage:** PHP `$_SESSION`
- **Styling:** Custom CSS (with animation support)


---

## ▶️ How to Play

1. Open `index.html` in your browser.
2. Enter names for **3 players**, and choose:
   - Number of dice 🎲
   - Number of throws 🔁
3. Click **Play**, and you’ll be redirected to the gameplay screen.
4. Click **Throw** each round until all rounds are completed.
5. The final page will show the **winner** (or a draw) and play a fireworks animation 🎆.

---

## 🧠 Game Logic Summary

- Each player rolls a defined number of dice.
- The roll result is added to the player's score.
- After all throws, the player with the highest total wins.
- Draws are detected and declared appropriately.

---

## 📦 Requirements

- PHP 7.0 or later
- Local or hosted server (e.g. XAMPP, MAMP, WAMP)

---

## 🧪 Running the Game Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/dice-game.git


