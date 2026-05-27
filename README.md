<div align="center">

<img src="posters/1.png" alt="MindGlow — Mini Arcade" width="450"/>

# 🕹️ MindGlow

### An IoT-Powered Color Memory Game

**A smart and interactive cognitive training device — built with ESP32, sensors, and the Blynk cloud.**

[![Course](https://img.shields.io/badge/Course-CCSW432%20IoT-purple)]()
[![University](https://img.shields.io/badge/University-Jeddah-blue)]()
[![Hardware](https://img.shields.io/badge/Hardware-ESP32-orange)]()
[![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C)]()

</div>

---

## 🌟 What is MindGlow?

**MindGlow** is a smart, interactive color memory game designed to enhance visual memory, concentration, and reaction speed through engaging sequence-based gameplay.

The game operates without traditional start buttons. Instead, it begins automatically when a player approaches the device — detected by an ultrasonic proximity sensor. Once detected, the player activates the game by tapping a touch sensor, creating a modern, intuitive, and seamless experience.

During each round, MindGlow displays a sequence of illuminated colors using LED buttons. The player must observe the pattern and reproduce it by pressing the buttons in the same order. With every successful attempt, the sequence becomes progressively longer and faster.

If the player makes a mistake, the system provides visual feedback through a distinctive light pattern, ends the round, and displays the final score on the LCD screen.

## 🎯 Project Objectives

- **Cognitive training** — Improve memory, concentration, and reaction speed through interactive play
- **IoT integration** — Demonstrate practical application of Internet of Things technologies in embedded systems
- **Data tracking** — Collect player performance data via cloud services for monitoring and analysis
- **Seamless interaction** — Use sensors to remove the need for traditional start mechanisms

## 🛠️ Hardware Components

| Component | Description |
|-----------|-------------|
| 🧠 ESP32 Development Board | Main microcontroller |
| 🔌 ESP32 Extension Shield | Easier wiring and expansion |
| 📺 16×2 LCD with I2C | Score and feedback display |
| 👆 Touch Sensor | Game activation |
| 📡 Ultrasonic Sensor | Player proximity detection |
| 🔘 6 × Push Buttons | Player input |
| 💡 6 × 10 mm LEDs | Color sequence display |
| 🔋 2 × 18650 Batteries (5000mAh) | Power supply |
| ⚡ 18650 Battery Holder + DC Jack | Power management |

## 💻 Software & Tools

- **C++** — Embedded programming for ESP32
- **Blynk** — IoT cloud platform for real-time data and remote monitoring

## ⚙️ How the System Works

```
1. Player approaches device
        ↓
2. Ultrasonic sensor detects presence
        ↓
3. Player taps touch sensor → Game starts
        ↓
4. System generates random color sequence
        ↓
5. LEDs light up in pattern
        ↓
6. Player reproduces sequence using buttons
        ↓
7. System checks input → Success or Game Over
        ↓
8. Score displayed on LCD + sent to cloud
```

## ☁️ IoT & Cloud Integration

MindGlow uses **Blynk** to monitor player performance in real time. Scores and gameplay data are transmitted wirelessly, enabling:

- 📊 **Performance tracking** across multiple sessions
- 📈 **Score comparison** between players
- 🔄 **Real-time data updates** to the cloud
- 🚀 **Foundation for future analytics**

## 🛣️ Future Enhancements

- 🏆 **Online leaderboard** connecting multiple MindGlow devices
- 📱 **Mobile app integration** for player profiles and history
- ⚙️ **Adjustable difficulty levels** based on player performance
- 👥 **Multiplayer mode** and timed challenge modes

## 📸 Build Gallery

The complete development process — from buttons to final wiring — is documented in the project report:

📑 **[Read the Full Project Report](docs/MindGlow_Project.pdf)**

You can also browse the [posters](posters/) folder for our marketing visuals.

## 👥 Team BrightMinds

**Course:** CCSW432 — Internet of Things  
**Section:** SE3  
**Institution:** University of Jeddah — College of Computer Science and Engineering  
**Semester:** Fall 2026

| Name | ID |
|------|-----|
| Remas Nafea Alsulami | 2310961 |
| Enas Hamed Alqarni | 2314104 |
| Jana Yasser Akkad | 2313200 |
| Rawan Bakashwin | 2312084 |

## 🎓 Conclusion

MindGlow demonstrates how IoT technologies can be applied to create interactive, engaging, and intelligent systems. By combining hardware components, embedded programming, and cloud connectivity, the project successfully delivers a fun memory-based game while showcasing practical IoT concepts learned in CCSW432.

---

<div align="center">

**Built with 💜 by Team BrightMinds**

</div>
