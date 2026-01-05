# Pacman Game (C++ / SFML)

A desktop-based Pacman game implemented in **C++** using **SFML**, focusing on real-time rendering, keyboard input handling, and modular game logic design.

This project demonstrates core game development concepts including collision detection, game loops, state management, and object-oriented design.

---

## 🎮 Features

- Real-time player movement controlled via keyboard input
- Tile-based map system with wall collision detection
- Pellet consumption and score tracking
- Enemy (ghost) interaction and game-over detection
- Screen wrap-around behavior (classic Pacman tunnel logic)
- Modular C++ class design for maintainability

---

## 🧠 Technical Highlights

- **SFML Graphics & Input**
  - Sprite rendering using `sf::Texture` and `sf::Sprite`
  - Real-time keyboard input via `sf::Keyboard`
  - Window rendering loop with `sf::RenderWindow`

- **Game Logic**
  - Custom collision detection system to prevent wall traversal
  - Direction-based movement with speed control
  - Map parsed from a script-based layout
  - Game-over detection when Pacman collides with a ghost

- **Object-Oriented Design**
  - `Pacman` class for player logic
  - `Ghost` class for enemy behavior
  - `Collision` utilities for map-based interactions
  - `Global` structures for shared constants and data types

---

## 🚀 How to Build & Run

### Requirements
- C++17 or later
- SFML (Graphics, Window, System)
- CMake

### Build Instructions

```bash
git clone https://github.com/spencertyy/PacMan.git
cd PacMan
mkdir build
cd build
cmake ..
make
./testSFML
```

Note:
-	SFML must be installed and properly linked on your system.
- The executable name may vary depending on your build configuration.


## 🕹 Controls

- **Up Arrow**: Move up  
- **Down Arrow**: Move down  
- **Left Arrow**: Move left  
- **Right Arrow**: Move right  

---

## 📌 Learning Outcomes

- Practical experience building a real-time interactive application in **C++**
- Hands-on use of **SFML** for graphics rendering and keyboard input handling
- Improved understanding of **collision detection**, **game loops**, and **state management**
- Experience organizing a medium-sized C++ project using **CMake**

---

## 🧑‍💻 Author

**Yuyao Tu / Terry Cao** 

This project was developed as part of a C++ programming course to explore game development fundamentals and object-oriented design principles.

---

## 📄 License

This project is for **educational purposes only**.
