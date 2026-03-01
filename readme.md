# 🏓 Ping Pong Game (Python Turtle)

A classic 2-player Ping Pong (Pong) game built using Python's Turtle graphics library.  
This project features real-time ball movement, paddle controls, collision detection, scoring system, and bounce sound effects.

---

## 🎮 Features

- 🏓 Two-player gameplay
- ⌨️ Smooth keyboard controls
- ⚡ Real-time ball physics
- 🔁 Paddle and wall collision detection
- 🔊 Bounce sound effects
- 🧮 Live score tracking
- 🖥️ Retro-style game interface

---

## 🛠️ Technologies Used

- Python 3.x
- Turtle Graphics (Built-in)
- Winsound (for bounce sound effects)

---

## 📂 Project Structure


PING_PONG/
│
├── pong1.py
├── bounce.wav
└── README.md


---

## 🚀 How To Run The Game

### 1️⃣ Clone the Repository


git clone https://github.com/ekank123/PING_PONG.git


### 2️⃣ Navigate to Project Folder


cd PING_PONG


### 3️⃣ Run the Game


python pong1.py


Make sure Python 3.x is installed on your system.

---

## 🎮 Controls

| Player | Move Up | Move Down |
|--------|----------|------------|
| Player A | W | S |
| Player B | ↑ Arrow | ↓ Arrow |

---

## 🧠 How The Game Works

- The ball moves using `dx` and `dy` velocity values.
- When the ball hits the top or bottom wall, its vertical direction reverses.
- When the ball hits a paddle, its horizontal direction reverses.
- If the ball crosses the left or right boundary, the opponent scores a point.
- The scoreboard updates dynamically after each point.
- A bounce sound plays on collisions.

---

## 🎯 Future Improvements

- Add AI opponent mode
- Add difficulty levels
- Add winning condition (First to 5)
- Add background music
- Increase ball speed progressively

---

## 👨‍💻 Author

**Ekank**  
GitHub: https://github.com/ekank123

---

## 📜 License

This project is open-source and free to use for learning purposes.