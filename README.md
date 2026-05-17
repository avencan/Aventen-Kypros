# Aventen Kypros

> **The world's first Arduino-compatible board with WiFi 6, Gigabit Ethernet, HDMI output, and 802.15.4 — all on a board smaller than a Raspberry Pi Zero.**

![Aventen Kypros](board-hero.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Arduino Compatible](https://img.shields.io/badge/Arduino-Compatible-teal.svg)](https://arduino.cc)
[![Status: Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-orange.svg)](https://aventeninnovations.com)

---

## What Is Kypros?

Kypros is a next-generation development board built on the **NXP MIMXRT1176** — the most powerful Cortex-M microcontroller ever made. It is fully Arduino IDE compatible, supports FreeRTOS and NXP MCUXpresso SDK, and is designed to be the last board you ever need to buy.

Nobody else has built an Arduino board on the RT1176. Kypros is first.

---

## Specifications

| Feature | Detail |
|---|---|
| **MCU** | NXP MIMXRT1176DVMAB |
| **Architecture** | Dual-core: Cortex-M7 @ 1GHz + Cortex-M4 @ 400MHz |
| **RAM** | 2MB on-chip SRAM |
| **PSRAM** | 8MB APS6404L (QPI) |
| **Flash** | 16MB W25Q128JVPIQ |
| **Storage** | MicroSD card slot (SDXC — up to 2TB) |
| **WiFi** | WiFi 6 (802.11ax) — Murata Type 2EL |
| **Bluetooth** | Bluetooth 5.3 — Murata Type 2EL |
| **802.15.4** | Thread / Matter / Zigbee — Murata Type 2EL |
| **Ethernet** | Gigabit (RTL8211E PHY + RJ45 breakout header) |
| **HDMI** | 1080p @ 60fps via ADV7535 HDMI bridge (Micro HDMI) |
| **Display** | MIPI DSI 2-lane (header) |
| **Camera** | MIPI CSI 2-lane (FPC connector) |
| **Audio** | SGTL5000 stereo codec (98dB SNR) + IMP23ABSU MEMS mic |
| **USB** | USB-C (OTG — host + device) |
| **GPIO** | Standard 2.54mm headers, both long edges |
| **CAN** | CAN-FD |
| **Battery** | LiPo JST connector + onboard charging |
| **Dimensions** | 69mm × 18mm |
| **Price** | £199.99 |

---

## Why Kypros?

### vs Teensy 4.1
Teensy 4.1 is a great board. But it has no WiFi, no Bluetooth, no Ethernet, no HDMI, and no 802.15.4. Kypros has all of these at 1GHz on a smaller board.

### vs Arduino Portenta X8
Portenta X8 runs Linux and needs a carrier board to do anything useful. Kypros is instant-on like a microcontroller, Arduino IDE compatible out of the box, and £35 cheaper.

### vs ESP32
ESP32 is WiFi 4, single-core-class performance, no HDMI, no Gigabit, no 802.15.4. Kypros is in a different league.

### The Real Story
We built [Formosa Sync](https://github.com/avencan/Aventen-Formosa-Sync) on RT1060. Then we asked: *what if we used the chip nobody else has touched yet, threw out every compromise, and built something genuinely new?*

The RT1176 is the most powerful Cortex-M chip on the market. No Arduino board uses it. Kypros is first.

---

## What Can You Build?

- 🎮 **Retro gaming console** — HDMI out + USB/BT gamepad + SD card full of ROMs
- 🖥️ **Wireless desktop computer** — HDMI monitor + BT keyboard + BT mouse
- 🔒 **Privacy-first security camera** — MIPI camera + 1TB SD + local AI person detection. No cloud. No China.
- 🚁 **Autonomous drone** — M4 handles stabilisation, M7 handles navigation + vision AI
- 🏠 **Smart home hub** — 802.15.4 mesh + WiFi 6 + "Hey Aventen" wake word. No subscription.
- 🌐 **Programmable WiFi 6 router / network gateway** — WiFi 6 + Gigabit Ethernet
- 🤖 **Robot brain** — CAN-FD + camera + WiFi telemetry + dual-core real-time control
- 📡 **IoT gateway** — bridge 802.15.4 mesh sensors to WiFi 6 / Gigabit cloud
- 🔊 **AI voice assistant** — wake word on M4 (private, on-device) → complex AI over WiFi 6
- 🏭 **Industrial controller** — CAN-FD + Ethernet + real-time M4 + deterministic RTOS
- 📸 **AI dashcam** — CSI camera + SD recording + WiFi upload + on-device detection
- 📟 **Wearable / handheld** — MIPI display + BT + battery + ultra-low-power M4

---

## Software

Kypros supports three levels of development:

| Level | Environment | Who it's for |
|---|---|---|
| 🟢 Arduino IDE | `digitalWrite()`, `WiFi.h`, drag-and-drop UF2 | Beginners, makers |
| 🟡 Aventen SDK | FreeRTOS, full hardware APIs, dual-core | Intermediate developers |
| 🔴 NXP MCUXpresso SDK | Bare metal, maximum control | Professional / production |

### Arduino Core
The Kypros Arduino Core (`aventen/kypros`) provides:
- Full `digitalWrite()`, `analogRead()`, `Serial`, `Wire`, `SPI`
- `WiFi.h` — WiFi 6 via Murata 2EL over SDIO
- `KyprosBLE.h` — Bluetooth 5.3
- `KyprosMesh.h` — 802.15.4 / Thread / Matter
- UF2 drag-and-drop flashing — no JTAG needed

### Board Manager
```
https://aventeninnovations.com/package_aventen_index.json
```
*(Coming soon)*

---

## Open Source

Kypros follows the **Raspberry Pi model** of open source:

- ✅ **Schematic PDF** — publicly available
- ✅ **Arduino Core** — fully open source (MIT)
- ✅ **Aventen SDK** — fully open source
- ❌ **KiCad source files** — private (competitive IP)
- ❌ **Gerber files** — private

---

## Links

- 🌐 Website: https://aventeninnovations.com
- 🛒 Crowd Supply (waitlist): https://www.crowdsupply.com/aventen/aventen-formosa-sync
- 📰 Press (Formosa Sync): https://www.hackster.io/news/aventen-formosa-sync-is-a-high-performance-dev-board-running-up-to-1-ghz-f2581d62fd3c
- 📧 Contact: val.fidanci@aventen.co

---

## Status

> 🔶 **Pre-production** — hardware in final design review. Software development in progress. Join the waitlist at [aventeninnovations.com](https://aventeninnovations.com) to be first to know when Kypros launches.

---

## About Aventen

Aventen Innovations Ltd is a British hardware company building the next generation of maker development boards. Founded by Valentino Fidanci.

*Built in Britain. 🇬🇧*

---

*© 2026 Aventen Innovations Ltd — MIT Licence*
