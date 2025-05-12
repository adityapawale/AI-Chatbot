# AI-Chatbot
# 🤖 AI Chatbot with ESP32

This project is a hardware-based AI Chatbot using two ESP32 modules. It features voice interaction through a microphone and speaker, and is powered by a rechargeable battery with a charging module. An IR sensor is also used to detect presence and trigger interaction.

## 📦 Components Used

- 🧠 **2x ESP32 modules** – for processing and communication
- 🎤 **Microphone** – captures user voice input
- 🔊 **Speaker** – plays audio responses from the chatbot
- 🔋 **Rechargeable battery** – powers the entire system
- ⚡ **Charging module (TP4056 or similar)** – safely charges the battery
- 👁️ **IR Sensor** – detects user presence to activate the chatbot

## ⚙️ Features

- Voice-based interaction using ESP32
- Chatbot activates automatically when someone approaches (via IR sensor)
- Portable and rechargeable hardware design
- Speaker outputs chatbot responses
- Modular design for easy hardware modification

## 🛠️ How It Works

1. The **IR sensor** detects motion and wakes up the chatbot.
2. The **microphone** records the user's question.
3. The **ESP32** processes the input or sends it to an external AI service.
4. The **ESP32** receives the response and plays it back through the **speaker**.
5. Powered by a **rechargeable battery**, the system is portable and energy-efficient.

## 🔋 Power Setup

- Battery is connected via a **TP4056 charging module**.
- Ensure safe voltage levels for the ESP32 and connected peripherals.
- Battery can be charged via USB using the charging module.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-chatbot-esp32.git
