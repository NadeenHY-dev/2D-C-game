# 2D Platform Game – OOP2 Project

A small 2D platform-style game written in **C++** using **SFML**.  
This project was built to demonstrate **Object-Oriented Programming (OOP)** concepts such as inheritance, polymorphism, modular design, and separation between game logic and UI.

---

## 🎮 Features
- Main menu, settings, help, pause, and high score screens  
- Single-player and two-player modes  
- Different platform types (moving, breakable, moving-breakable)  
- Special effects / powerups (bat, black hole, trampoline, wings, heart)  
- Sound effects and background music  
- High score saving to file  

---

## 📁 Project Structure


include/ → Header files (class declarations)
src/ → Source files (implementations + main.cpp)
resources/ → Images, sounds, fonts, highScore.txt
cmake/ → CMake helper scripts
CMakeLists.txt → Build configuration


### Main Components
- **GameBase** → Core game objects (Player, Map, GameObject, Logic)
- **PlatformType** → Different platform behaviors
- **Effects** → Powerups and special objects
- **Screens** → Menu and game state management
- **Tools** → Sound manager, loading manager, sidebar UI

---

## 🛠 Requirements
- C++20 compatible compiler  
- CMake (3.26+)  
- SFML 2.6 (graphics + audio)

---

## ▶️ How to Build

From the project root:

```bash
cmake -S . -B build -DSFML_DIR="PATH/TO/SFML/lib/cmake/SFML"
cmake --build build
🚀 How to Run

After building, run the executable from the build folder:

./oop2_ex03

(Windows users may run oop2_ex03.exe from the Debug/Release folder.)

Make sure the resources folder is copied into the build directory (CMake handles this automatically).

📚 Purpose

This project was created as part of an Object-Oriented Programming course to practice:

Class hierarchy design

Game loop structure

Resource management

Screen/state management

Using external libraries (SFML)
