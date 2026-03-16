# Balloon Shooter Game 🎈🔫

A vibrant, interactive 2D balloon shooting game developed in **C++** using the **iGraphics** library. Test your accuracy and reflexes as you progress through increasingly challenging levels!

## 🎮 Overview
Balloon Shooter is a classic arcade-style game where players must pop moving balloons using a mouse-controlled crosshair. The game features a clean UI, custom graphics, and a progressive difficulty system.

## ✨ Features
- **Multiple Difficulty Levels**: Choose from Level 1, Level 2, or Level 3, each with increasing speeds and balloon counts.
- **Dynamic Gameplay**: Balloons move across the screen in various patterns, requiring precise timing.
- **Life System**: Players start with a set number of lives. Accuracy is key—missing a shot costs a life!
- **Interactive UI**: Custom-designed aim (crosshair), heart-based life indicators, and level-specific backgrounds.
- **Graphics Powered by iGraphics**: Built using the iGraphics library (an OpenGL/GLUT wrapper) for smooth rendering and bitmap support.

## 🕹️ How to Play
1. **Launch the Game**: Start a "New Game" from the main menu.
2. **Select Level**: Choose your desired difficulty (Level 1 is easiest, Level 3 is hardest).
3. **Aim & Shoot**:
   - Move your mouse to control the **Aim**.
   - **Left-Click** to shoot at the balloons.
4. **Win Condition**: Pop all balloons in the level to win!
5. **Lose Condition**: If you run out of lives (by missing targets), the game is over.

| Level | Balloons to Pop | Speed |
| :--- | :--- | :--- |
| **Level 1** | 5 | Standard |
| **Level 2** | 10 | Faster |
| **Level 3** | 15 | Challenging |

## 🛠️ Technologies Used
- **Language**: C++
- **Graphics Library**: iGraphics (OpenGL & GLUT)
- **Assets**: Custom BMP bitmaps for characters, backgrounds, and UI elements.

## 🚀 Setup & Installation
To run this project locally, follow these steps:

### Prerequisites
- **Visual Studio**: Recommended version is **Visual Studio 2010**. It also works with 2012–2019 if VS 2010 is installed.
- **OpenGL/GLUT**: Ensure the necessary `.lib` and `.h` files are correctly linked.

### Installation Steps
1. **Clone the project** to your local machine.
2. **Setup Libraries**: 
   - Copy the `.lib` files from the project folder to your Windows SDK library path (e.g., `C:\Program Files (x86)\Microsoft SDKs\Windows\v7.0A\Lib`).
   - Ensure `GLUT32.DLL` is in the same directory as the executable or in `C:\Windows\System32`.
3. **Open the Solution**: Load `Balloon_shooter.sln` in Visual Studio.
4. **Compile & Run**:
   - Do **not** upgrade the Windows SDK Version or Platform Toolset if prompted.
   - Press `F5` to build and run the game.

## 📁 Project Structure
- `iMain.cpp`: Core game logic, rendering loops, and input handling.
- `iGraphics.h`: Graphics library header.
- `Instructions.txt`: Detailed compatibility and setup notes.
- `/Balloon_shooter`: Contains all source files and bitmap assets (Backgrounds, Balloons, UI).

## 📄 License
This project is for educational purposes. Feel free to explore and modify the code!

---
*Developed with ❤️ using C++ and iGraphics.*
