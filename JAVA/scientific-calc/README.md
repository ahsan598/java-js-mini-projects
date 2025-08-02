# 🧮 Scientific Calculator – Java Swing GUI Mini Project


### 📌 Project Overview

This desktop-based **Scientific Calculator**, developed using **Java Swing**, replicates the functionality of modern scientific calculators. It supports standard arithmetic operations (addition, subtraction, multiplication, division), scientific functions (sin, cos, tan, log, power), and includes a custom **Speed–Distance–Time calculator** accessible via the File menu.

Designed as part of a Java GUI learning series, the project focuses on modular component design, event-driven programming, and clean layout management using Swing’s panel-based structure.

---

### 🎯 Objective

- Create a GUI-based scientific calculator using Java Swing
- Implement real-time mathematical operations through button events
- Integrate custom calculators (like **Speed–Distance–Time**) using menus
- Strengthen Java GUI skills through a modular approach


### 🧱 Architecture

The application follows a **modular, event-driven architecture** commonly used in GUI-based Java programs:

- **UI Layer:** Built using Java Swing components like `JFrame`, `JPanel`, `JButton`, `JTextField`, and `JMenuBar`. The UI is structured using nested panels to organize buttons and display fields.
- **Event Handling:** All button clicks are handled via `ActionListener`, triggering different logic based on the source of the event.
- **Computation Logic:** Calculator operations (basic and scientific) are performed using native Java methods (`Math.sin()`, `Math.pow()`, etc.). The Speed–Distance–Time calculator is implemented as a separate logic module under the menu.
- **Menu System:** A `JMenuBar` is used to integrate additional tools like **Speed–Distance–Time** within the same application context.

This separation ensures clarity between the **interface**, **logic**, and **event handling**, making the code more maintainable and scalable.

![scientific-calc](https://github.com/ahsan598/js-mini-projects/blob/master/JAVA/scientific-calc/screenshots/scientific-calc.png)


### 📂 Project Structure

```sh
scientific-calc/
├── src/                     # Java source code
│   └── Main.java
├── screenshots/             # UI screenshot for README
│   └── scientific-calc.png
├── build.xml                # Build script (used by NetBeans)
└── README.md                # Project overview
```


### 🛠️ Technologies Used

| Tool / Language | Purpose                         |
|-----------------|---------------------------------|
| Java            | Core programming language       |
| Java Swing      | GUI layout and component design |
| IntelliJ / NetBeans | Java development environment |


### 🖥️ Run via IDE:

1. Open the project folder in your preferred Java IDE (IntelliJ, NetBeans, Eclipse)
2. Open `ScientificCalc.java`
3. Run the file

### 💻 Run via Command Line:

```bash
javac ScientificCalc.java
java ScientificCalc
```

### 📚 Key Concepts Explored

- Java Swing (JButton, JPanel, JMenu, JTextField)
- Event handling using ActionListener
- Layout management for UI panels
- Math class usage (Math.sin(), Math.log(), etc.)
- Modular calculator logic for advanced features


### 🧠 Learnings

- Practiced creating interactive GUIs using Java Swing
- Improved understanding of event-driven programming
- Implemented real-world logic (Speed–Distance–Time) into GUI design
- Learned to break down features into manageable components


### 📝 Summary

This project extends a basic calculator into a full scientific calculator, integrating advanced mathematical functions and real-world calculators within a user-friendly GUI. It serves as a great exercise in building scalable Java Swing applications.
