# 🚦 Traffic Light Simulator (Java)

A clean, graphical **Traffic Light Simulator** built with **Java Swing**.  
This application simulates a standard 3-phase traffic light (Red → Yellow → Green) with a modern, polished UI.

![Java](https://img.shields.io/badge/Java-100%25-red?logo=java)
![Swing](https://img.shields.io/badge/GUI-Swing-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🎮 Features

- **Realistic 3-phase cycle** – Red → Yellow → Green → Yellow → Red (auto-switches every 2 seconds).
- **Manual override** – Click on the light panel to manually force the next phase.
- **Visual status indicator** – Displays the current light name and countdown timer.
- **Sleek dark theme** with rounded UI elements for a modern look.
- **Lightweight** – runs on any system with Java installed.

---

## 🖥️ How to Run

Make sure you have **Java 8 or higher** installed.

1. **Clone the repository**  
   ```bash
   git clone https://github.com/amardelil/traffic-light-java.git
   cd traffic-light-java
```

1. Compile the code
   ```bash
   javac TrafficLight.java
   ```
2. Run the application
   ```bash
   java TrafficLight
   ```

---

🎯 Controls

Action Input
Manually cycle to next light Click anywhere on the GUI
Auto-cycle Enabled by default
Exit program Close the window

---

🛠️ Tech Stack

· Java (JDK 11+)
· Swing – for GUI components
· AWT – for event handling and graphics

---

🧠 What I Learned

· Building state machines (enum for light states).
· Using javax.swing.Timer for periodic updates.
· Handling mouse events for user interaction.
· Creating custom painted components with Graphics2D.

---

🚀 Future Improvements

· Add a pedestrian walk signal (red/green man).
· Implement traffic light synchronization (multiple lights).
· Add sound alerts for color changes.

---

👤 Author

Amar Deili

· GitHub: @amardelil
· Portfolio: amardelli.github.io

---

