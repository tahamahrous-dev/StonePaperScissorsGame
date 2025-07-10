# 🎮 Stone-Paper-Scissors Game (C++) ✊📄✂️

A simple console-based **Stone-Paper-Scissors** game where you play against the computer.  
Built as part of a C++ learning journey with a focus on **logic, user interaction, and code structure**.

---

## 📘 Project Overview

This game lets a player choose between **Stone**, **Paper**, or **Scissors** and plays multiple rounds against a computer opponent. The game tracks the outcome of each round and declares a final winner. It also includes visual feedback via console color changes.

---

## 🛠️ Features

- 👨‍💻 Single-player vs. computer
- 🔢 Play up to 10 rounds per session
- 🎨 Console color changes:
  - 🟩 Green → Player wins
  - 🟥 Red → Computer wins
  - 🟨 Yellow → Draw
- 📊 Game summary at the end
- 🔁 Replay support

---

## 🚀 Getting Started

### 🔧 Prerequisites

- C++ Compiler (e.g. `g++`, Visual Studio, Code::Blocks)
- Windows OS (required for `system("color")` and `system("cls")`)

### 🧪 How to Compile and Run

#### Using g++ (Command Line):

```bash
g++ FirstProject_StonePaperScissorsGame.cpp -o StonePaperScissors
./StonePaperScissors
```

#### Using Visual Studio:
- Create a new Console Project.
- Copy-paste the code into `main.cpp`.
- Build and run.

---

## 📂 Project Structure

```
/StonePaperScissorsGame
├── FirstProject_StonePaperScissorsGame.cpp
└── README.md
```

---

## 🧠 Technical Highlights

- `enum` for clear type-safe choices (`Stone`, `Paper`, `Scissors`)
- `struct` to manage round and game state (`stRoundInfo`, `stGameResults`)
- Console feedback using `system("color")` and `system("cls")`
- Random choice generation using `rand()` seeded with `time(NULL)`
- Modular functions for clarity and reusability

---

## 📸 Screenshots

### 🎮 Gameplay Interface
![Gameplay Screenshot](images/gameplay-screenshot.png)

### 🏁 Final Game Summary
![Final Results Screenshot](images/final-results-screenshot.png)

> You can update the `/images/` folder with your actual screenshots.

---

## 📌 Sample Output

```text
Round [2] begins:
Your Choice: [1]:Stone, [2]:Paper, [3]:Scissors ? 1

Player1  Choice: Stone
Computer Choice: Scissors
Round Winner   : [Player1]
```

> ✅ Screen background changes color based on result (Windows only).

---

## 🏁 Game Summary Example

```text
_____________________ [Game Results] _____________________

Game Rounds        : 5
Player1 won times  : 3
Computer won times : 1
Draw times         : 1
Final Winner       : Player1
```

---

## 📣 How to Give Feedback (Peer Review Friendly)

If you're reviewing this code, your feedback is welcome!  
Here are a few areas you could help improve:

- 🧠 **Logic clarity**: Is the game logic easy to follow?
- 🧱 **Code structure**: Are the functions and enums organized well?
- ✏️ **Naming**: Any suggestions to improve readability?
- 🎮 **Gameplay experience**: Is the user interaction smooth?

Feel free to open an issue or leave a comment!

---

## 🙏 Credits

Created as part of a Algorithms_Problem_Solving_Level_2 course with guidance from **Dr. Mohammed Abu-Hadhoud**.  
Designed for hands-on practice in algorithm design, decision-making, and struct management.

---

## 🪪 License

This project is open-source and free to use for **educational** and **non-commercial** purposes.

---


## ©️ Copyright and License  
**Copyright © 2025 Taha Mahrous. All rights reserved.**

---

> ✨ Happy Coding & Let the best move win! 🎉
