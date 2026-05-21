<div align="center">

<img src="https://aventeninnovations.com/board-green-front.png" alt="Aventen Kypros — front" width="600"/>

# Aventen Kypros

### The most powerful Arduino-compatible board ever made.

Dual-core 1GHz. WiFi 6. HDMI out. Camera in. Gigabit Ethernet. Thread & Zigbee. Audio codec. LiPo power. GPU-accelerated graphics. Edge AI. All on a board smaller than a Raspberry Pi Zero.

[![Join Waitlist](https://img.shields.io/badge/Join%20Waitlist-aventeninnovations.com-blueviolet?style=for-the-badge)](https://aventeninnovations.com/#waitlist)
[![Status](https://img.shields.io/badge/Status-In%20Development%202026-orange?style=for-the-badge)](https://aventeninnovations.com)
[![Crowd Supply](https://img.shields.io/badge/Crowd%20Supply-Coming%20Soon-green?style=for-the-badge)](https://www.crowdsupply.com/aventen/aventen-formosa-sync)
[![Built in Britain](https://img.shields.io/badge/Built%20in%20Britain-🇬🇧-red?style=for-the-badge)](#)

</div>

---

## At a Glance

| | |
|---|---|
| **CPU** | NXP MIMXRT1176DVMAB — Cortex-M7 @ 1GHz + Cortex-M4F @ 400MHz |
| **RAM** | 2MB on-chip SRAM + 8MB PSRAM (APS6404L, QSPI 133MHz) |
| **Flash** | 16MB NOR Flash (W25Q128JVPIQ) + MicroSD (up to 2TB) |
| **Wireless** | Murata Type 2EL — WiFi 6 (802.11ax, 601Mbps) + BT 5.3 + Zigbee + Thread + Matter |
| **Ethernet** | RTL8211E — Gigabit 10/100/1000Mbps |
| **HDMI** | 1080p @ 60fps via ADV7535 MIPI-to-HDMI bridge — Micro HDMI (Type D) |
| **Camera** | MIPI CSI-2 2-lane FPC connector — on-board |
| **Audio** | SGTL5000 stereo codec, 98dB SNR |
| **USB** | USB-C OTG (power + data + programming) + USB 2.0 host header |
| **GPIO** | Dual-row headers — SPI, I²C, UART, CAN-FD, PWM, ADC — 3.3V logic |
| **Power** | LiPo JST connector + USB-C charging + RTC backup |
| **Debug** | SWD/JTAG header — J-Link, ST-Link, CMSIS-DAP |
| **Form Factor** | 69 × 18mm — 8-layer HDI PCB |
| **IDE Support** | Arduino IDE (official board package) · PlatformIO · MCUXpresso |
| **Price** | £199.99 / ~$266 |

---

## Gallery

<div align="center">

| Front | Back |
|---|---|
| <img src="https://aventeninnovations.com/board-front.png" width="350"/> | <img src="https://aventeninnovations.com/board-back.png" width="350"/> |

| PCB Layout | 3D Render |
|---|---|
| <img src="https://aventeninnovations.com/pcb-layout.png" width="350"/> | <img src="https://aventeninnovations.com/board-green-back.png" width="350"/> |

</div>

---

## Why Kypros?

### ⚡ Dual-Core Powerhouse
Cortex-M7 @ 1GHz + Cortex-M4F @ 400MHz. Run your application on M7 and real-time control on M4 — simultaneously. Both cores share memory but operate independently. No other Arduino board comes close.

### 📡 Six Radios on One Board
WiFi 6 (802.11ax) at 601Mbps, Bluetooth 5.3, and 802.15.4 for Zigbee, Thread, and Matter mesh networks — all at the same time. Via Murata Type 2EL (IW612 tri-radio combo).

### 🖥️ Native HDMI Output
1080p @ 60fps via micro HDMI. The **only Arduino-compatible board with native HDMI output.** Build dashboards, kiosks, game consoles, or instrument clusters. Plug into any monitor or TV. No adapter. No shield.

### 📷 Camera Input
MIPI CSI-2 2-lane FPC connector directly on board. Run computer vision, object detection, QR scanning, or video preview — all processed on-chip with 8MB PSRAM for frame buffers.

### 🎵 Studio-Grade Audio
SGTL5000 codec, 98dB SNR, headphone amp, line in/out. Build synthesisers, effects pedals, or voice assistants.

### 🌐 Gigabit Ethernet
RTL8211E PHY — 10/100/1000Mbps. Full Gigabit networking. 10× faster than Teensy 4.1's 100Mbps.

### 🔋 Battery-Native
LiPo connector + charging circuit + RTC backup. Designed for portable from day one. Charge via USB-C, run on battery, wake from RTC alarm. No power management shield required.

### 🧠 Edge AI Ready
TensorFlow Lite Micro + NXP eIQ + 2D VGLite GPU at 500MHz. Run ML models on-device — image classification, keyword spotting, anomaly detection. Hardware-accelerated graphics.

---

## Nothing Else Comes Close

### vs. Premium & Industrial Boards

|  | **KYPROS** | Arduino Portenta X8 | BeagleBone AI-64 | NVIDIA Jetson Orin Nano |
|---|---|---|---|---|
| **CPU** | **M7 @ 1GHz + M4 @ 400MHz** | A7 @ 800MHz + M7 + M4 | Dual A72 @ 2GHz + R5F | 6-core A78AE @ 1.5GHz |
| **RAM** | **8MB PSRAM + 2MB SRAM** | 512MB LPDDR4 | 2GB LPDDR4 | 4GB LPDDR5 |
| **WiFi** | ✅ **WiFi 6** | WiFi 5 | WiFi 5 | ❌ (M.2 add-on) |
| **Bluetooth** | ✅ **BT 5.3** | BT 5.1 | BT 5.0 | ❌ |
| **Zigbee / Thread / Matter** | ✅ **Native** | ❌ | ❌ | ❌ |
| **HDMI Output** | ✅ **1080p — built-in** | ❌ shield required | ❌ | ✅ via adapter |
| **Gigabit Ethernet** | ✅ **Built-in** | ❌ shield required | ✅ Dual GbE | ✅ |
| **Audio Codec** | ✅ **SGTL5000** | ❌ | ❌ | ❌ |
| **LiPo Native** | ✅ | ❌ | ❌ | ❌ |
| **Arduino IDE** | ✅ **Board package** | ✅ | ❌ | ❌ |
| **Real-Time OS** | ✅ **FreeRTOS (bare-metal)** | Linux + M4 RTOS | Linux only | Linux only |
| **Form Factor** | **69×18mm** | 66×25mm | 87×54mm | Module + carrier board |
| **Price** | **£199.99** | ~£175 | ~£140 | ~£375 (dev kit) |

> Kypros costs **less** than a Jetson Orin Nano dev kit, **similar** to a Portenta X8 — but adds WiFi 6, BT 5.3, Thread/Matter, native HDMI, audio codec, LiPo charging, and Arduino IDE support that none of them have.

### vs. Maker Boards

|  | **KYPROS** | Teensy 4.1 | ESP32-S3 | ESP32-P4 | Arduino UNO R4 | Pi Pico 2W | Pi Zero 2W | Portenta H7 |
|---|---|---|---|---|---|---|---|---|
| **CPU Speed** | **1GHz + 400MHz** | 600MHz | 240MHz | 400MHz | 48MHz | 150MHz | 1GHz (Linux) | 480MHz |
| **RAM / Memory** | **8MB PSRAM + 16MB Flash** | 16MB opt | 2–8MB | 768KB | 32KB | 520KB | 512MB LPDDR2 | 8MB SDRAM |
| **WiFi** | ✅ **WiFi 6** | ❌ | WiFi 4 | ❌ | WiFi 4 | WiFi 4 | WiFi 4 | WiFi 4 |
| **Bluetooth** | ✅ **BT 5.3** | ❌ | BT 5.0 | ❌ | BT 5.0 | BT 5.2 | BT 4.2 | BT 5.1 |
| **Zigbee / Thread / Matter** | ✅ **Native** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **HDMI Output** | ✅ **1080p** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ (Linux) | ❌ adapter |
| **Camera (CSI)** | ✅ **On-board** | ❌ | USB only | ✅ MIPI | ❌ | ❌ | ✅ (Linux) | ❌ shield |
| **Ethernet** | ✅ **Gigabit** | ✅ 100Mbps | ❌ | ❌ | ❌ | ❌ | ❌ USB only | ❌ shield |
| **Audio Codec** | ✅ **SGTL5000** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **LiPo Native** | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **GPU / Accelerator** | ✅ **VGLite 500MHz** | ❌ | ❌ | ✅ basic | ❌ | ❌ | ✅ VideoCore | ❌ |
| **Arduino IDE** | ✅ **Board package** | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ |
| **Form Factor** | **69×18mm** | 61×18mm | varies | varies | 68×53mm | 51×21mm | 65×30mm | 66×25mm |
| **Price** | **£199.99** | ~£35 | ~£6 | ~£30–45 | ~£27 | ~£6 | ~£15 | ~£80 |

> Kypros is the only Arduino-compatible board with WiFi 6, HDMI 1080p output, native Zigbee/Thread/Matter, Gigabit Ethernet, on-board audio codec, and LiPo battery charging — all in one ready-to-use 69×18mm form factor. No shields. No carrier boards. No compromises.

---

## What Will You Build?

| 🏠 Smart Home Hub | 🤖 Robotics & Vision | 🎵 Audio & Synthesis |
|---|---|---|
| WiFi 6 + BT + Zigbee + Thread + Matter. Run every smart home protocol natively. No Pi, no dongles. | Camera CSI + 1GHz + real-time M4. Run CV on M7 and motor control on M4 simultaneously. | SGTL5000 stereo codec + MicroSD. Synthesisers, audio processors, and voice assistants. |

| 📊 Industrial IoT | 🎮 Gaming Console | 🔒 Security Camera |
|---|---|---|
| CAN-FD + Gigabit Ethernet + WiFi 6 + battery backup. Edge compute nodes with 1GHz real-time. | Retro gaming via HDMI + USB gamepad + SD card ROMs. NES/SNES/GBA/PSP. | MIPI camera + 1TB SD card + WiFi 6. 24/7 local recording with motion detection. 100% private — no cloud. |

| 🚁 Drone & UAV | 📡 Mesh Networking | 🖥️ Desktop Terminal |
|---|---|---|
| 802.15.4 swarm mesh + real-time M4 flight controller + WiFi 6 telemetry. | Thread + Matter + BT 5.3 mesh. Build infrastructure that talks to everything. | Kypros + HDMI + USB keyboard/mouse + WiFi 6. A real computer in 69×18mm. |

👉 **[Explore all 100+ use cases →](https://aventeninnovations.com/use-cases.html)**

---

## Overclocking

Kypros is designed to run at **1GHz stock** — already faster than a fully overclocked Formosa Sync. But the RT1176 can go further.

| Mode | M7 Clock | M4 Clock | Notes |
|---|---|---|---|
| **Stock** | 1.0 GHz | 400 MHz | Default — stable, cool, tested |
| **Overclocked** | **up to 1.4 GHz** | up to 600 MHz | Community-tested, silicon lottery applies |

> ⚠️ Overclocking is unsupported and voids warranty. It requires bumping core voltage and adequate thermal management. Results vary per unit.

Formosa Sync needed overclocking to hit 1GHz. Kypros does 1GHz in its sleep — then keeps going.

---

## Software

Kypros supports three levels of development:

| Layer | Platform | Best for |
|---|---|---|
| 🟢 Beginner | **Arduino IDE** — official board package | Simple sketches, learning, drag-and-drop UF2 |
| 🟡 Intermediate | **Aventen SDK** — FreeRTOS + full API | Custom firmware, real-time apps |
| 🔴 Advanced | **NXP MCUXpresso SDK** — bare metal | Production firmware, maximum control |

```cpp
// It really is this simple
#include <WiFi.h>

void setup() {
  WiFi.begin("MyNetwork", "password");
  while (WiFi.status() != WL_CONNECTED) delay(500);
  Serial.println("Connected on WiFi 6 — " + WiFi.localIP().toString());
}
```

---

## Specs Deep Dive

<details>
<summary><b>Processor</b></summary>

| Parameter | Value |
|---|---|
| SoC | NXP MIMXRT1176DVMAB |
| Primary Core | ARM Cortex-M7 @ 1 GHz |
| Secondary Core | ARM Cortex-M4F @ 400 MHz |
| Architecture | Dual-core asymmetric multiprocessing |
| FPU | Double-precision (M7) + Single-precision (M4) |
| DSP | Hardware DSP instructions on both cores |
| GPU | 2D VGLite — 500MHz hardware pixel pipeline |
| Internal SRAM | 2 MB on-chip |

</details>

<details>
<summary><b>Memory</b></summary>

| Parameter | Value |
|---|---|
| PSRAM | APS6404L-3SQR-ZR — 8MB, QSPI 133MHz |
| Flash | W25Q128JVPIQ — 16MB NOR, QSPI 133MHz, XIP |
| Internal SRAM | 2 MB on-chip |
| MicroSD | SDIO interface — up to 2TB |

</details>

<details>
<summary><b>Wireless — Murata LBES5PL2EL-923 (Type 2EL)</b></summary>

| Parameter | Value |
|---|---|
| Chipset | NXP IW612 tri-radio combo |
| WiFi | 802.11a/b/g/n/ac/ax (WiFi 6), dual-band 2.4 + 5 GHz |
| WiFi Speed | Up to 601 Mbps (MCS11, 80MHz channel) |
| TX Power | 18 dBm |
| Bluetooth | BT 5.3 BR/EDR/LE |
| 802.15.4 | Zigbee, Thread, Matter — native |
| Host Interface | SDIO (WiFi), UART (BT), SPI (802.15.4) |
| Antenna | Kyocera AVX M830520 tri-band + U.FL port |

</details>

<details>
<summary><b>Audio</b></summary>

| Parameter | Value |
|---|---|
| Codec | NXP SGTL5000XNLA3 |
| SNR | 98 dB |
| Sample Rate | Up to 96 kHz |
| Outputs | Line-out stereo + headphone amp |
| Inputs | Line-in stereo + mic-in |

</details>

---

## Open Source

Kypros follows the **Raspberry Pi model**:
- ✅ Schematic PDF — publicly available
- ✅ Arduino Core — open source
- ✅ All libraries — open source
- 🔒 KiCad source files — private (competitive advantage)
- 🔒 Gerber files — shared only with licensed fab (PCBWay)

---

## Status

| Milestone | Status |
|---|---|
| Schematic design | ✅ Complete |
| PCB layout | 🔄 In progress |
| Prototype fabrication | 📅 Planned Q3 2026 |
| Arduino Core development | 🔄 In progress |
| Pre-orders / waitlist | ✅ Open |

---

## Links

| | |
|---|---|
| 🌐 **Website** | [aventeninnovations.com](https://aventeninnovations.com) |
| 📋 **Waitlist** | [aventeninnovations.com/#waitlist](https://aventeninnovations.com/#waitlist) |
| 🛒 **Crowd Supply** | [crowdsupply.com/aventen/aventen-formosa-sync](https://www.crowdsupply.com/aventen/aventen-formosa-sync) |
| 📰 **Hackster.io** | [Aventen covered on Hackster](https://www.hackster.io/news/aventen-formosa-sync-is-a-high-performance-dev-board-running-up-to-1-ghz-f2581d62fd3c) |
| 💬 **Contact** | [hello@aventeninnovations.com](mailto:hello@aventeninnovations.com) |
| 🏠 **Previous board** | [Aventen-Formosa-Sync](https://github.com/avencan/Aventen-Formosa-Sync) |

---

<div align="center">

**Built in Britain 🇬🇧 — Loved everywhere.**

*Aventen Innovations Ltd — Eastbourne, UK*

© 2026 Aventen Innovations Ltd · [aventeninnovations.com](https://aventeninnovations.com)

</div>
