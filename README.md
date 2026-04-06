# 🤖 DeskBuddy (DEBU)

> A compact AI-powered desk assistant robot powered by ESP32-S3, integrated with [OpenClaw](https://github.com/) as the intelligence backbone.

---

## ⚠️ Project Status: 30% Complete

This project is still in early development. Many components are not yet finalized. Contributions are welcome!

---

## 📖 About

**DeskBuddy (DEBU)** is a small desktop robot designed to act as a voice-enabled AI assistant. It listens to your voice, processes commands through the OpenClaw assistant service, and responds with synthesized speech — all from your desk.

---

## 🧠 Hardware

| Component | Description |
|-----------|-------------|
| **ESP32-S3** | Main microcontroller / brain |
| **INMP441** | Omnidirectional MEMS I2S Microphone Module |
| **PCM5102A** | DAC Decoder Board with I2S Interface |
| **Speaker** | Mini 3 Watt Speaker |
| **OLED Display** | 128x64 0.96 inch I2C LCD Display |

---

## 🔗 Integration

- **OpenClaw** — AI assistant backend that handles natural language processing and response generation.

---

## 🚀 Features (Planned)

- [x] Hardware component selection
- [ ] Voice input via INMP441 microphone
- [ ] Text-to-Speech (TTS) output via PCM5102A + speaker
- [ ] OLED display for status/expressions
- [ ] OpenClaw assistant integration
- [ ] Wake word detection
- [ ] 3D printed enclosure

---

## 🔄 In Progress

| Item | Status |
|------|--------|
| TTS Service | 🔄 In Progress |
| Firmware | 🔄 In Progress |

---

## ❌ Not Yet Ready

| Item | Status |
|------|--------|
| Bill of Materials (BOM) | ⏳ Pending |
| 3D Case Design | ⏳ Pending |
| Wiring Guide | ⏳ Pending |
| Firmware (complete) | ⏳ Pending |

---

## 🗂️ Project Structure

```
DEBU/
├── firmware/         # ESP32-S3 firmware source code
├── hardware/         # Schematics & wiring guide
├── 3d-case/          # 3D model files (.f3d / .stl)
└── docs/             # Documentation & BOM
```

---

## 🛠️ Getting Started

> **Coming soon.** Full setup guide will be available once firmware and wiring guide are finalized.

---

## 🤝 Contributing

Contributions are greatly appreciated! Here's where you can help:

- **3D Case Design** → We are actively looking for contributors familiar with **Autodesk Fusion** to design the enclosure for DEBU.
- **Firmware** → ESP32-S3 / Arduino / ESP-IDF experience welcome.
- **Documentation** → Help write the wiring guide and BOM.

> 📌 **We are looking for contributors to help drive the further development of this project.**

Feel free to open an issue or submit a pull request.

---

## 📄 License

Apache License 2.0

---

## 📬 Contact

satya@gravitoncode.com

---
