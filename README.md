<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,100:1f6feb&height=180&section=header&text=ESP32%20OLED%20PAC-MAN&fontSize=42&fontColor=ffffff&animation=fadeIn"/>

# 👾 ESP32 OLED Pac-Man Game

### Retro arcade game running on ESP32 + SSD1306 OLED display

<br>

<img src="https://img.shields.io/badge/ESP32-Project-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/OLED-SSD1306-black?style=for-the-badge">
<img src="https://img.shields.io/badge/Arduino-C%2B%2B-green?style=for-the-badge">

<br><br>

<img src="images/gameplay.gif" width="700"/>

<br><br>

🎮 Smooth gameplay • 👻 Ghost AI • 🔊 Retro sounds • ⚡ ESP32 Powered

</div>

---

# 🚀 About the Project

This project is a mini Pac-Man style game made for **ESP32 + SSD1306 OLED** with:

- Analog joystick control
- Ghost chasing AI
- Pellet collection
- Score and lives system
- Sound effects with buzzer
- Retro arcade style graphics

---

# 🔗 Full Project

<div align="center">

<a href="https://www.youtube.com/@ztr0n1cs">
<img src="https://img.shields.io/badge/YouTube-ztr0n1cs-red?style=for-the-badge&logo=youtube">
</a>

<a href="https://beacons.ai/ztronics/">
<img src="[https://img.shields.io/badge/Beacons-Full_Funnel-purple?style=for-the-badge](https://cdn.beacons.ai/user_content/se1lA5rA76Q4rhyCHdSxinRd3j53/referenced_images/generated-images__link-in-bio__links-block__home__ad169c18-2ae2-4c0e-b985-a3079aa0837e__82ea0d1c-8c58-446f-9dab-51c5895523b9__81fe1859-a9f9-4b7e-badc-ef0c782b70b0.webp?t=1777334643357)">
</a>

<a href="https://www.instructables.com/member/ztr0nics/">
<img src="https://img.shields.io/badge/Instructables-Tutorial-orange?style=for-the-badge&logo=instructables">
</a>

<a href="https://www.pinterest.com/ztronics03/">
<img src="https://img.shields.io/badge/Pinterest-More_Projects-red?style=for-the-badge&logo=pinterest">
</a>

<a href="https://github.com/webzf/">
<img src="https://img.shields.io/badge/GitHub-webzf-black?style=for-the-badge&logo=github">
</a>

</div>

---

# ✨ Features

<table>
<tr>
<td>🕹️ Analog joystick movement</td>
<td>👾 Animated Pac-Man sprites</td>
</tr>

<tr>
<td>👻 Smart chasing ghosts</td>
<td>🍒 Pellet collection system</td>
</tr>

<tr>
<td>🔊 Arcade sound effects</td>
<td>❤️ Lives and score HUD</td>
</tr>

<tr>
<td>🎬 Startup intro animation</td>
<td>⚡ Smooth float movement</td>
</tr>
</table>

---

# 📺 Parts Used

<div align="center">

<a href="https://beacons.ai/ztronics/">
<img src="https://img.shields.io/badge/🛒%20ESP32%20Dev%20Board-View%20Part-blue?style=for-the-badge">
</a>

<br><br>

<a href="https://beacons.ai/ztronics/">
<img src="https://img.shields.io/badge/📟%20SSD1306%20OLED-View%20Part-black?style=for-the-badge">
</a>

<br><br>

<a href="https://beacons.ai/ztronics/">
<img src="https://img.shields.io/badge/🕹️%20Joystick%20Module-View%20Part-green?style=for-the-badge">
</a>

<br><br>

<a href="https://beacons.ai/ztronics/">
<img src="https://img.shields.io/badge/🔊%20Passive%20Buzzer-View%20Part-orange?style=for-the-badge">
</a>

</div>

---

# 🔌 Wiring

## OLED Display

| OLED | ESP32 |
|---|---|
| VCC | 3.3V |
| GND | GND |
| SDA | GPIO 21 |
| SCL | GPIO 22 |

## Joystick

| Joystick | ESP32 |
|---|---|
| VRX | GPIO 35 |
| VRY | GPIO 34 |
| SW | GPIO 27 |
| VCC | 3.3V |
| GND | GND |

## Buzzer

| Buzzer | ESP32 |
|---|---|
| + | GPIO 13 |
| - | GND |

---

# 📚 Libraries

Install these libraries from Arduino IDE Library Manager:

U8g2  
Wire

---

# 🎮 Controls

| Action | Control |
|---|---|
| Move Pac-Man | Analog Joystick |
| Restart Game | Press Joystick Button |

---

# 🧠 Ghost AI

The ghosts chase the player using a simple system:

- Detect available paths
- Avoid walls
- Calculate shortest distance
- Change direction dynamically

---

# 📸 Preview

<div align="center">

<img src="https://i.pinimg.com/736x/72/ab/d5/72abd5ed6c715fbb44924c2e4aa33a06.jpg" width="320"/>
<img src="https://i.pinimg.com/736x/52/66/23/526623ed8ece861a59e05a1753826480.jpg" width="320"/>

</div>

---

# ⚡ Upload Guide

1. Open Arduino IDE  
2. Install ESP32 board package  
3. Install U8g2 library  
4. Select your ESP32 board  
5. Upload the code  
6. Enjoy retro gaming 👾

---

# 📂 Repository Structure

esp32-oled-pacman-game/

├── images/  
│   ├── gameplay.gif  
│   ├── gameplay.jpg  
│   └── wiring.png  

├── esp32-oled-pacman-game.ino  
├── README.md  
└── LICENSE  

---

# ⭐ Support

If you liked this project:

⭐ Star the repository  
📺 Subscribe on YouTube  
🚀 Visit the full funnel  
💬 Share the project  

---

# 📜 License

MIT License

---

<div align="center">

# 👾 Retro Gaming on ESP32

Made with ❤️ using Arduino + ESP32

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0f0f0f&height=120&section=footer"/>

</div>
