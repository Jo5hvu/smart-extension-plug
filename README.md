# Smart Extension Plug - 3 Socket WiFi Controller

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: ESP32](https://img.shields.io/badge/Platform-ESP32-blue)](https://www.espressif.com/en/products/socs/esp32)
[![MQTT](https://img.shields.io/badge/MQTT-3.1.1-orange)](https://mqtt.org/)

Control 3 AC sockets remotely using Wemos D1 R32 ESP32, MQTT, and a beautiful web dashboard. Accessible from anywhere in the world.

![Dashboard Preview](docs/dashboard_preview.png)

## ✨ Features

- **3 Independent Sockets** - Control each outlet separately
- **Remote Access** - Control from anywhere via MQTT
- **Real-time Status** - Instant feedback on device states
- **Master Controls** - Turn all sockets ON/OFF simultaneously
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Secure MQTT** - Supports TLS/SSL for cloud brokers
- **Event Logging** - Complete history of all commands
- **Zero Configuration** - Auto-reconnects on WiFi loss

## 🛠️ Hardware Required

| Component | Quantity | Notes |
|-----------|----------|-------|
| Wemos D1 R32 (ESP32) | 1 | Any ESP32 dev board works |
| Relay Module (5 V logic) | 3 | Optoisolated recommended |
| Extension Plug | 1 | 3-socket minimum |
| 5V Power Supply | 1 | For ESP32 and relays |
| Jumper Wires | 20+ | Female-to-female |
| Enclosure | 1 | Plastic project box |

## 📊 Wiring Diagram
 
