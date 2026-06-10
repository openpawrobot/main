# OpenPaw

OpenPaw is an open-source AI companion robot for pets.

- 100% open source
- Built in public
- MIT licensed
- Organization: https://github.com/openpawrobot

## Project Vision

Millions of pets spend hours alone every day. Most pet products only provide passive camera streaming. OpenPaw is focused on active interaction, behavior-aware intelligence, and better day-to-day pet engagement.

## Demo

- Final video cut: https://youtu.be/kn2AgR_2DU8?si=tc3Vv8gAWHyQVW9I

## Why OpenPaw

| Traditional Pet Tech | OpenPaw |
|---|---|
| Passive camera feed | Active AI interaction |
| Expensive and proprietary | Free and open source |
| Watch-only experience | Play, engage, and monitor |
| Closed ecosystem | Community-driven development |
| No wellness data | Health and behavior insights |

## Current Development Status

| Feature | Status | Phase |
|---|---|---|
| Camera System (OV2640) | Complete | Phase 1 |
| OTA Firmware Updates | Complete | Phase 1 |
| Distance Sensor (VL53L0X) | Complete | Phase 1 |
| Laser Module | Complete | Phase 1 |
| Firmware Architecture | Active | Phase 1 |
| Microphone Integration (I2S) | In Progress | Phase 2 |
| Speaker System | In Progress | Phase 2 |
| Temperature and Humidity Sensor | In Progress | Phase 2 |
| Motor Control (Servo + DC) | In Progress | Phase 2 |
| Captive Portal WiFi Setup | Planned | Phase 2 |
| Speech AI (LLM Integration) | Planned | Phase 3 |
| Behavior Analysis Engine | Planned | Phase 3 |
| Wellness Intelligence Dashboard | Planned | Phase 3 |
| Flutter Mobile Application | Planned | Phase 4 |
| Production Hardware (PCBs) | Planned | Phase 5 |

## System Architecture

```text
OPENPAW CORE
  AI Companion Robot for Pets (ESP32)

Core Firmware Layer
  ESP32, FreeRTOS, PlatformIO, Arduino Framework

Subsystems
  Sensors: Camera OV2640, VL53L0X, Temperature/Humidity, I2S Mic, Speaker, Motor Control
  AI Layer: Computer Vision, Behavior AI, Wellness AI, Speech LLM, Decision Engine, Data Insights
  Services: OTA, Firebase Cloud, REST APIs, Web Dashboard, Mobile App, Cloudflare

Companion Experience
  Pet engagement, wellness monitoring, remote access, AI interaction, laser play, environment tracking
```

## Technology Stack

### Firmware

- C
- C++
- ESP32
- PlatformIO
- Arduino

### Backend and AI

- Python
- FastAPI
- Firebase
- Google Cloud

### Mobile and Frontend

- Flutter
- React
- JavaScript
- HTML5

### DevOps and Tools

- GitHub Actions
- Docker
- Git
- SQLite
- Cloudflare
- Figma

## Repository Ecosystem

| Repository | Purpose | Status |
|---|---|---|
| [openpaw-firmware](https://github.com/openpawrobot/openpaw-firmware) | ESP32 firmware (C/C++, FreeRTOS) | Active |
| [openpaw-hardware](https://github.com/openpawrobot/openpaw-hardware) | PCB, CAD, and mechanical design | Active |
| [openpaw-app](https://github.com/openpawrobot/openpaw-app) | Flutter mobile application | Planned |
| [openpaw-website](https://github.com/openpawrobot/openpaw-website) | Website and waitlist | Active |
| [openpaw-ml](https://github.com/openpawrobot/openpaw-ml) | AI models and wellness signals | Planned |
| [openpaw-docs](https://github.com/openpawrobot/openpaw-docs) | Documentation and architecture | Active |
| [openpaw-marketing](https://github.com/openpawrobot/openpaw-marketing) | Build-in-public automation | Active |

## Quick Start (Firmware)

```bash
git clone https://github.com/openpawrobot/openpaw-firmware
cd openpaw-firmware

# Set target board (ESP32 / ESP32-S3 / ESP32-CAM)
idf.py set-target esp32

# Configure project (WiFi credentials, pins, modules)
idf.py menuconfig

# Build firmware
idf.py build

# Flash device and open serial monitor
idf.py flash monitor
```

## Contributing

OpenPaw welcomes contributors in firmware, robotics, hardware, mobile, AI/ML, docs, and testing.

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feat/amazing-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "feat: add amazing feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feat/amazing-feature
   ```
5. Open a pull request with a clear description.

## Community

- X: https://x.com/OpenPawOfficial
- Reddit: https://reddit.com/user/OpenPawAI
- YouTube: https://youtube.com/@openpaw
- Linktree: https://linktr.ee/openpawrobot
- GitHub: https://github.com/openpawrobot

## Acknowledgements

- Espressif for the ESP32 platform
- The open-source community
- Contributors and testers
- Pet owners supporting development feedback

## License

MIT
