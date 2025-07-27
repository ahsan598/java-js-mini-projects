# 🕒 Digital Clock Application | Java GUI Practice Project


### 📌 Project Overview

This application uses **Java's Swing framework** to build a dynamic **Digital Clock** that continuously updates the system time on a clean UI. It is part of a GUI practice series focused on helping beginners understand event handling, layout management, and real-time updates in desktop apps.

---

### 🎯 Objective

- To practice Java Swing for GUI development
- To create a standalone desktop application using Java
- To understand how to update UI components in real-time using `Timer`
- To build a lightweight utility using Java-only tools


### 🧱 Architecture

Since this is a simple Java desktop application, the architecture follows a **single-layered design**:

- `DigitalClock.java`: Handles UI creation, time fetching, and updating the label
- `javax.swing.Timer`: Used to update the time every second
- No external dependencies or backend systems involved

![digital-clock](https://github.com/ahsan598/js-mini-projects/blob/master/JAVA/digital-clock/screenshots/digital-clock.png)


### 📂 Project Structure

```sh
digital-clock/
├── src/                     # Java source code
│   └── Main.java
├── screenshots/             # UI screenshot for README
│   └── digital-clock.png
├── build.xml                # Build script (used by NetBeans)
└── README.md                # Project overview
```


### 🛠️ Technologies Used

| Tool / Language | Purpose                        |
|-----------------|--------------------------------|
| Java            | Core programming language      |
| Java Swing      | GUI development                |
| Timer API       | Real-time time update          |
| IntelliJ / NetBeans | Java IDE for development   |



### 🖥️ Run via IDE:

1. Open the project folder in your preferred Java IDE (IntelliJ, NetBeans, Eclipse)
2. Open `DigitalClock.java`
3. Run the file


### 💻 Run via Command Line:

```bash
javac DigitalClock.java
java DigitalClock
```

### 📚 Key Concepts Explored

- Swing components (JFrame, JLabel, Font, Timer)
- Real-time system time retrieval
- Event-driven programming
- GUI layout and window management
- Java's built-in Date and SimpleDateFormat APIs


### 🧠 Learnings

- Hands-on experience with Java Swing layouts and components
- Learned how to schedule real-time updates using javax.swing.Timer
- Understood how to format system time using SimpleDateFormat
- Improved skills in writing clean, readable, and modular Java code


### 📝 Summary

The Digital Clock project is a simple yet effective example of using Java Swing for real-time GUI applications. It fulfills its objective of providing hands-on practice with timers and UI updates, and serves as a good starting point for anyone exploring Java GUI development.
