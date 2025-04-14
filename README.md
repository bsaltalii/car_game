# 🚗 Terminal Car Game

*Terminal Car Game* is a fast-paced arcade-style terminal game built in C++ using the `ncurses` library. The player dodges incoming traffic, levels up with higher scores, and can save and load progress mid-game — all in the command line.

---

## 🎯 Purpose

This project brings a retro driving game experience to life in the terminal.  
It also demonstrates threading, file operations, real-time UI rendering, and menu management in C++.

---

## 🧩 App Architecture

Modularly designed with clear responsibilities:

| 🧱 Component      | 📌 Description                                |
|------------------|-----------------------------------------------|
| *Car struct*     | Represents a car with shape, speed, and color |
| *Game struct*    | Holds game state, player car, score, queue    |
| *UI & Game Loop* | ncurses-based rendering and control flow      |
| *File IO*        | Save/load game state and high scores          |
| *Menus*          | Main, settings, and scoreboards               |

---

## 🚀 Features

<ul>
  <li>🕹️ <strong>Real-Time Controls</strong>: Use <code>&lt;/&gt;</code> or <code>A/D</code> to dodge incoming cars.</li>
  <li>🎯 <strong>Dynamic Leveling</strong>: Level up every <strong>400 points</strong>. With each new level, incoming cars move faster, increasing the challenge.</li>
  <li>💾 <strong>Save & Load</strong>: Pause and continue your game anytime.</li>
  <li>🎨 <strong>Custom Cars</strong>: Random car sizes, colors, and symbols.</li>
  <li>🌲 <strong>Decorative Trees</strong>: Visual detail alongside the road.</li>
  <li>🏁 <strong>Collision Detection</strong>: Ends game on crash with other cars.</li>
</ul>

---

## 📸 Screenshots

> Play the game directly in your terminal — here’s a sample preview.

<p align="center">
  <img src="https://github.com/bsaltalii/car_game/blob/main/screenshots/home.png" width="600"/>
  <img src="https://github.com/bsaltalii/car_game/blob/main/screenshots/instructions.png" width="600"/>
  <img src="https://github.com/bsaltalii/car_game/blob/main/screenshots/settings.png" width="600"/>
  <img src="https://github.com/bsaltalii/car_game/blob/main/screenshots/points.png" width="600"/>
  <img src="https://github.com/bsaltalii/car_game/blob/main/screenshots/game_1.png" width="600"/>
  <img src="https://github.com/bsaltalii/car_game/blob/main/screenshots/game_2.png" width="600"/>
  <img src="https://github.com/bsaltalii/car_game/blob/main/screenshots/game_3.png" width="600"/>
</p>

---

## 🖥️ Platform

•⁠  ⁠Linux / Unix-based terminals  
•⁠  ⁠macOS terminal support  

---

## 📦 Installation

### Prerequisites

•⁠  ⁠G++ compiler  
•⁠  ⁠`ncurses` library installed  
•⁠  ⁠Make or terminal access  

### Steps

```bash
# Clone the repository
git clone https://github.com/bsaltalii/terminal-car-game.git

# Navigate to the project directory
cd terminal-car-game

# Compile the game
g++ car_game.cpp -lncurses -lpthread -o cargame

# Run the game
./cargame
```

---

---

## 👤 Developer

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/bsaltalii">
          <img src="https://avatars.githubusercontent.com/u/96692734?v=4" width="100px;" alt="Developer Avatar"/>
          <br /><sub><b>Burak Saltalı</b></sub>
        </a>
      </td>
    </tr>
  </tbody>
</table>

---

## 📝 License

This project is licensed under the *MIT License*.  
See the [LICENSE](LICENSE) file for more information.
