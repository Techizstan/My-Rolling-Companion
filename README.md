# My Rolling Companion
This is a smart wheelchair project that integrates voice commands, manual  control, and automated obstacle avoidance. The wheelchair is controlled via a custom-built Android app that connects to the hardware using Bluetooth. This solution is designed to aid physically challenged individuals in navigating their environment more independently.

---

## Demo Video

Watch the full working demo:  
https://youtube.com/shorts/wgEIt59e-DI?si=VCiNE3fT3zECSc7r
> Includes Bluetooth pairing, app controls (manual, auto, voice), and real-time movement of the wheelchair.

---

## Features

- *Bluetooth Connectivity* – Seamless pairing between the Android app and wheelchair hardware.
- *Manual Mode* – On-screen directional buttons (Forward, Backward, Left, Right).
- *Automatic Mode* – Obstacle avoidance using ultrasonic sensors.
- *Voice Control Mode* – Supports voice commands like “forward,” “backward,” “stop,” etc.
- *Emergency Stop* – Safety-first feature to instantly stop movement.
- *LED Indicators* – Indicate active mode.

---

## How It Works

### 1. *Bluetooth Pairing*
- Pair your phone with the Bluetooth module (e.g., HC-05).
- Open the app and connect to the paired device.

### 2. *Manual Mode*
- Use on-screen buttons to move Forward, Backward, Left, and Right.
- Useful for direct control or tight spaces.

### 3. *Automatic Mode*
- The wheelchair automatically avoids obstacles using ultrasonic sensors.
- Ideal for safe navigation indoors.

### 4. *Voice Mode*
- Give voice commands like “forward,” “backward,” “left and ” “right”
- Uses phone's speech recognition and sends commands via Bluetooth.

---

## Tech Stack & Components

### Hardware:
- Arduino UNO / Nano
- Motor Driver Module (L293D)
- Bluetooth Module (HC-05)
- Ultrasonic Sensors (HC-SR04)
- 12V DC Motors
- 12V Battery
- Wheels + Chassis
- Push Buttons (Emergency Stop, Power ON/OFF)
- LEDs for indicators

### Software:
- Arduino IDE
- MIT App Inventor (for Android app)
- Voice Recognition via Android app

---
