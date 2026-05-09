# ESP32 OLED Pac-Man Game 👾

A smooth mini Pac-Man style game running on an ESP32 with a 128x64 SSD1306 OLED display, joystick control, animated sprites, enemy AI, sound effects and retro arcade vibes.

---

## ✨ Features

- 🕹️ Analog joystick movement
- 👻 Ghost AI chasing system
- 🍒 Pellet collection
- 🔊 Retro buzzer sounds
- ❤️ Lives & score system
- 🎬 Animated intro screen
- 📺 SSD1306 OLED graphics
- ⚡ Smooth movement using float physics
- 🔁 Restart button support

---

## 🧰 Hardware Required

| Component | Quantity |
|---|---|
| ESP32 Dev Board | 1 |
| SSD1306 OLED 128x64 I2C | 1 |
| Analog Joystick Module | 1 |
| Passive Buzzer | 1 |
| Jumper Wires | Some |

---

## 🔌 Wiring

### OLED Display

| OLED | ESP32 |
|---|---|
| VCC | 3.3V |
| GND | GND |
| SDA | GPIO 21 |
| SCL | GPIO 22 |

### Joystick

| Joystick | ESP32 |
|---|---|
| VRX | GPIO 35 |
| VRY | GPIO 34 |
| SW | GPIO 27 |
| VCC | 3.3V |
| GND | GND |

### Buzzer

| Buzzer | ESP32 |
|---|---|
| + | GPIO 13 |
| - | GND |

---

## 📚 Libraries

Install these libraries from Arduino Library Manager:

- U8g2
- Wire

---

## 🚀 Upload Instructions

1. Open Arduino IDE
2. Install ESP32 board package
3. Install required libraries
4. Select your ESP32 board
5. Upload the code
6. Enjoy retro gaming 🎮

---

## 🎮 Controls

| Action | Control |
|---|---|
| Move | Analog Joystick |
| Restart Game | Press Joystick Button |

---

## 🧠 Ghost AI

The ghosts use a simple pathfinding system:

- Checks available directions
- Calculates distance to player
- Selects shortest path
- Avoids walls automatically

---

## 📸 Preview

## 🎬 YouTube Short

Watch the build video here:

[https://youtube.com/shorts/XXXXXXXXXXX](https://youtube.com/shorts/ijL8A58yPtk?si=dTKPPlHSzpukIgOa)

---

## ⭐ Support

If you like this project:

- Star the repository ⭐
- Share the project
- Follow for more ESP32 creations

---

## 📜 License

MIT License
