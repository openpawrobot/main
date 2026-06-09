<div align="center">

# 🐾 OpenPaw

### The Open-Source AI Companion Robot For Pets

An affordable AI-powered companion robot designed to keep pets engaged, monitored, and connected while their humans are away.

**Built completely in public.**

<p align="center">
  <a href="YOUR_VIDEO_LINK">
    <img src="./assets/openpaw-demo.gif" width="900" alt="OpenPaw Demo">
  </a>
</p>

### 🎥 Watch OpenPaw In Action

[![Watch Demo](https://img.shields.io/badge/▶%20Watch%20Demo-YouTube-red?style=for-the-badge\&logo=youtube)](https://youtu.be/kn2AgR_2DU8?si=dEk0vnEUKTMzefOG)

<br>

[![Website](https://img.shields.io/badge/Website-pawme.ayvalabs.com-14b8a6?logo=googlechrome&logoColor=white)](https://pawme.ayvalabs.com)
[![X](https://img.shields.io/badge/X-@OpenPaw-000000?logo=x&logoColor=white)](https://x.com/OpenPaw)
[![Reddit](https://img.shields.io/badge/Reddit-u/OpenPawAI-FF4500?logo=reddit&logoColor=white)](https://www.reddit.com/user/OpenPawAI/)
[![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/openpaw)
[![Telegram](https://img.shields.io/badge/Telegram-join-26A5E4?logo=telegram&logoColor=white)](https://t.me/OpenPaw)
[![YouTube](https://img.shields.io/badge/YouTube-subscribe-FF0000?logo=youtube&logoColor=white)](https://youtube.com/@openpaw)

<br>

### 🚀 Building In Public • 🤖 Robotics • 🧠 AI • 🐾 Pets

</div>

---

> 🚧 **OpenPaw is currently under active development.**
>
> Follow our journey as we build an open-source AI companion robot for pets completely in public.
>
> Every success, failure, experiment, prototype, firmware update, hardware revision, and breakthrough is shared with the community.

---

# ❤️ Why OpenPaw Exists

Millions of pets spend hours alone every day.

Most pet cameras only allow owners to watch.

OpenPaw is different.

We're building an affordable AI companion capable of:

* 👀 Observing pet behavior
* 🎾 Playing and interacting
* 🧠 Learning routines and habits
* ❤️ Monitoring wellness indicators
* 📱 Keeping owners connected remotely
* 🤖 Delivering AI-powered companionship

And we're building everything completely open source.

---

# 🚧 Current Development Status

| Feature                | Status         |
| ---------------------- | -------------- |
| Camera System          | ✅ Complete     |
| OTA Firmware Updates   | ✅ Complete     |
| Distance Sensor        | ✅ Complete     |
| Firmware Architecture  | 🔄 Active      |
| Microphone Integration | 🟡 In Progress |
| Speaker System         | 🟡 In Progress |
| Temperature Sensor     | 🟡 In Progress |
| Motor Control          | 🟡 In Progress |
| Captive Portal         | ⏳ Planned      |
| Speech AI              | ⏳ Planned      |
| Flutter Mobile App     | ⏳ Planned      |
| Wellness Intelligence  | ⏳ Planned      |

---

# 📈 Build-In-Public Progress

### Recent Milestones

✅ Open-source ecosystem launched

✅ OTA firmware update system operational

✅ Distance sensing integrated

✅ Camera system working

✅ Public GitHub infrastructure established

🔄 Firmware migration and optimization

🔄 Sensor integration expansion

🔄 Robotics hardware iteration

---

# 🎥 Demo Videos

## Distance Sensor, Camera and OTA

📹 Watch Demo: https://www.reddit.com/u/OpenPawAI/s/4BdC17TnOp

---

# 🏗️ System Architecture

```text
                           OpenPaw
                               │
        ┌──────────────────────┼──────────────────────┐
        │                      │                      │
        ▼                      ▼                      ▼

    Firmware              Mobile App             Website
     ESP32                 Flutter               Next.js

        │
        ▼

     Sensor Layer

     ├── Camera
     ├── Distance
     ├── Temperature
     ├── Microphone
     ├── Speaker
     └── Motion

        │
        ▼

      AI Layer

     ├── Behavior Analysis
     ├── Wellness Detection
     ├── Voice Processing
     ├── Activity Tracking
     └── Future LLM Integration

        │
        ▼

    Companion Experience
```

---

# 📦 Repository Ecosystem

| Repository        | Purpose                                |
| ----------------- | -------------------------------------- |
| openpaw-docs      | Documentation, Roadmaps & Architecture |
| openpaw-firmware  | ESP32 Firmware                         |
| openpaw-hardware  | PCB, CAD & Mechanical Design           |
| openpaw-app       | Flutter Mobile Application             |
| openpaw-website   | Website & Waitlist                     |
| openpaw-ml        | AI Models & Wellness Signals           |
| openpaw-marketing | Build-In-Public Automation             |

---

## 🧭 Start here

| You want to… | Go to |
|---|---|
| Understand the vision & architecture | [openpaw-docs](https://github.com/ayvalabs/openpaw-docs) |
| Hack on the robot's brain | [openpaw-firmware](https://github.com/ayvalabs/openpaw-firmware) |
| Build/modify the hardware | [openpaw-hardware](https://github.com/ayvalabs/openpaw-hardware) |
| Work on the website / waitlist | [openpaw-website](https://github.com/ayvalabs/openpaw-website) |
| Explore the pet-health ML | [openpaw-ml](https://github.com/ayvalabs/openpaw-ml) |
| Help us post the build-in-public devlog | [openpaw-marketing](https://github.com/ayvalabs/openpaw-marketing) |

---

# 🗺️ Product Roadmap

## Phase 1 — Foundation

* [x] Open-source ecosystem
* [x] OTA updates
* [x] Camera integration
* [x] Distance sensing
* [x] Build-in-public workflow

## Phase 2 — Core Robotics

* [ ] Microphone
* [ ] Speaker
* [ ] Temperature sensing
* [ ] Captive portal
* [ ] Hardware optimization

## Phase 3 — AI Companion

* [ ] Speech AI
* [ ] Behavior analysis
* [ ] Wellness intelligence
* [ ] Voice interaction

## Phase 4 — User Experience

* [ ] Flutter mobile app
* [ ] Live camera feed
* [ ] Remote control
* [ ] User onboarding

## Phase 5 — Launch

* [ ] Beta testing
* [ ] Community validation
* [ ] Crowdfunding campaign
* [ ] Production hardware

---

# 🧠 Technology Stack

### Firmware

* ESP32
* ESP-IDF
* C / C++

### Mobile

* Flutter
* Dart

### Backend

* Python
* FastAPI

### AI

* OpenAI APIs
* Signal Processing
* Wellness Models

### Hardware

* Custom PCB
* Embedded Sensors
* Motors
* Camera Modules

---

# 🚀 Quick Start

```bash
git clone https://github.com/ayvalabs/openpaw-firmware

cd openpaw-firmware

idf.py set-target esp32

idf.py build

idf.py flash monitor
```

---

# 📊 Build In Public

We believe innovation happens faster in the open.

Every week we publish:

* Engineering progress
* Hardware updates
* Firmware improvements
* Development logs
* Prototype videos
* Technical learnings

Follow the journey and help shape OpenPaw.

---

# 🤝 Contributing

We're actively looking for:

* Robotics Engineers
* Embedded Engineers
* ESP32 Developers
* Flutter Developers
* AI Engineers
* PCB Designers
* CAD Designers
* Open Source Contributors
* Pet Owners willing to test

### Getting Started

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Open a pull request
5. Join the community

Every contribution matters.

---

# 🌟 Support The Project

If you believe in open-source robotics:

* ⭐ Star this repository
* 🍴 Fork the project
* 🔁 Share with friends
* 🛠️ Contribute code
* 🐾 Join the community
* 📢 Follow the journey

Your support helps accelerate development.

---

# 📄 License

MIT License

OpenPaw is open source and community driven.

See the LICENSE file for details.

---

<div align="center">

<div align="center">

# 🌎 Join The Community

Stay updated with every milestone, prototype, firmware update, and development log.

| Platform | Link |
|-----------|------|
| Reddit | https://www.reddit.com/user/OpenPawAI/ |
| X | https://x.com/OpenPaw |
| YouTube | https://youtube.com/@openpaw |
| Discord | https://discord.gg/openpaw |
| Telegram | https://t.me/OpenPaw |
---

### Building the future of pet companionship, one commit at a time.

❤️ Built in Public by OpenPaw

</div>
---
