# 🎮 Snake Game – Java Swing GUI Mini Project


### 📌 Project Overview

This project is a desktop-based implementation of the traditional **Snake Game**. It uses **Java Swing** for rendering the game window and components, while **multithreading** ensures smooth movement of the snake through a game loop. Players control the snake using arrow keys, consume food to grow, and aim to avoid collisions with the walls or themselves.

---

### 🎯 Objective

- Practice creating an interactive game using Java Swing
- Implement real-time animation and user input handling
- Understand and apply thread-based game loop logic
- Explore layout painting and custom component rendering


### 🧱 Architecture

The application uses a **single-window event-driven structure** with the following components:

- **Game Frame (`JFrame`)** – Main window container  
- **Game Panel (`JPanel`)** – Core drawing surface for the snake and food  
- **Game Loop (Thread)** – A separate thread continuously repaints the screen and updates game logic  
- **Input Handler** – Uses `KeyListener` to capture arrow key input  
- **Collision & Score Logic** – Detects food consumption and game-over conditions  

The architecture is modular, separating the logic into reusable classes for easier scaling and modification.

![snake-game](https://github.com/ahsan598/js-mini-projects/blob/master/JAVA/snake-game/screenshots/snake-game.png)


### 📂 Project Structure

```sh
snake-game/
├── src/                     # Java source code
│   └── Game.java
├── screenshots/             # UI screenshot for README
│   └── snake-game.png
├── build.xml                # Build script (used by NetBeans)
└── README.md                # Project overview
```

### 🛠️ Technologies Used

| Technology   | Purpose                             |
|--------------|-------------------------------------|
| Java         | Core programming language           |
| Java Swing   | GUI rendering and event handling    |
| Threads      | Real-time game loop and repainting  |
| IntelliJ / Eclipse | Java IDEs used for development |


### 🖥️ Run via IDE:

1. Open the project folder in your preferred Java IDE (IntelliJ, NetBeans, Eclipse)
2. Open `SnakeGame.java`
3. Run the file


### 💻 Run via Command Line:

```bash
javac SnakeGame.java
java SnakeGame
```


### 📚 Key Concepts Explored

- Real-time game development using Thread and Runnable
- Java Swing components: JPanel, JFrame, KeyListener, Graphics
- Collision detection logic (self and wall)
- Dynamic object movement and boundary checks
- Score calculation and game state management


### 🧠 Learnings

- Learned to use multithreading for smoother UI updates and game timing
- Faced challenges in detecting collisions and managing game-over states
- Improved control flow and modular design of real-time applications
- Understood how repainting in Swing works (paintComponent() vs repaint())


### 📝 Summary

This project successfully replicates the traditional Snake Game using Java Swing. It demonstrates effective use of GUI components, multithreading, and basic game logic. The project helped reinforce concepts of event-driven programming, animation, and custom rendering in desktop applications.
