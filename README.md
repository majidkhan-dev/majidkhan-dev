<h1 align="center">Hi, I'm Majid Khan</h1>

<p align="center">
  Embedded Systems Developer &nbsp;|&nbsp; PCB Designer &nbsp;|&nbsp; Full Stack Web &amp; Mobile Developer
</p>

<p align="center">
  BS Computer Engineering, COMSATS University Lahore (2026) &nbsp;|&nbsp; Lahore, Pakistan
</p>

<p align="center">
  I build embedded systems with ESP32 &amp; ESP-IDF and design PCBs in KiCad, from 2-layer power supplies to 4-layer microcontroller boards.
</p>

---

## Tech Stack

### Embedded & Hardware
<p align="center">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP--NOW-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=eclipsemosquitto&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32%20(basics)-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white"/>
</p>

**Protocols:** UART · I2C · SPI · MQTT · CoAP · BLE · ESP-NOW
**PCB:** schematic capture · 2- and 4-layer layout · custom footprints & libraries · DRC / DFM · Gerber & drill files · BOM

### Languages
<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
</p>

### Web, Mobile & Tools
<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
</p>

---

## Embedded Projects

### AI-based Smart HVAC System — Final Year Project
> LightGBM comfort model running on a Raspberry Pi 5 (also the MQTT broker); ESP32 sensor nodes with BME280, DS18B20 and PIR; the AC is controlled over IR towards Fanger PMV comfort setpoints; validated with hardware-in-the-loop simulation in DesignBuilder + EnergyPlus.
>
> **After graduation:** converted the model to plain C with m2cgen and moved inference and the MQTT broker onto a single **ESP32-S3**, removing the Raspberry Pi entirely.
>
> **Stack:** ESP32 / ESP32-S3 · ESP-IDF · Raspberry Pi · Python · LightGBM · m2cgen · MQTT · DesignBuilder · EnergyPlus
>
> [github.com/majidkhan-dev/ai-smart-hvac-system](https://github.com/majidkhan-dev/ai-smart-hvac-system)

### DOSEMATIC — Automatic Medication Dispenser *(commissioned, delivered as a product)*
> Motor rotates at dose time; TCRT5000 IR sensor detects the remaining dose and prevents double dispensing; delivered in a custom enclosure.
>
> **Stack:** ESP32 · ESP-IDF · ULN2003 · DC motor · TCRT5000 · SSD1306
>
> [github.com/majidkhan-dev/dosemetic-esp-code](https://github.com/majidkhan-dev/dosemetic-esp-code)

### Wireless Door Lock System
> Battery-powered two-node system using ESP-NOW (no Wi-Fi infrastructure needed); drives a solenoid lock with OLED and buzzer feedback.
>
> **Stack:** 2× ESP32 · ESP-IDF · ESP-NOW · solenoid lock · IRLZ34N · 18650 2S · OLED · buzzer
>
> [github.com/majidkhan-dev/wireless-door-lock-esp32](https://github.com/majidkhan-dev/wireless-door-lock-esp32)

### PIR Sensor Alarm System
> Motion detection with buzzer alert and 16×2 LCD display.
>
> **Stack:** ESP32 · ESP-IDF · PIR sensor · buzzer · 16×2 LCD
>
> [github.com/majidkhan-dev/pir-motion-alarm-esp32](https://github.com/majidkhan-dev/pir-motion-alarm-esp32)

---

## PCB Design (KiCad)

| Board | Details |
|---|---|
| **MCU Data Logger** | 4-layer board: ATmega328P, DS1337 RTC, 2× 24LC1025 I2C EEPROM; hierarchical schematic, custom component library, BOM, version-controlled in Git |
| **Solar Power Supply** | AP3015A boost converter (SMD), 2-layer; **passed NextPCB's DFM check** |
| **Breadboard Power Supply** | LM7805 (5 V) + LM317 (adjustable), barrel-jack input, 2-layer |
| **LED Torch** | First board: schematic → layout → Gerber/drill files |

<!-- TODO: add repo links / 3D render images for each board -->

---

## Web & Mobile Experience

**Full Stack Developer (Next.js)** · [EEPCSS](https://eepcss.com) · *03/2026*
Official website for a CSS/PMS exam preparation institute, server-side rendered for speed and SEO.

**Full Stack Developer (MERN)** · [Innovix99](https://innovix99.com) · *06–07/2025*
Admin dashboard with full CRUD and a dynamic SEO management system.

**Frontend Developer (React.js)** · [Ontrac IT Solutions](https://ontrac.biz) · *08–10/2023*
Bilingual (Arabic/English) company website with a client inquiry system.

**Projects:** [VetCare](https://github.com/majidkhan-dev/AppDev) — React Native app for farmers with AI vet consultation (Claude API) and Google Maps · [E-Commerce Backend](https://github.com/majidkhan-dev/ecommerce-backend) — Node.js, Express, MSSQL REST API

---

## Certifications

- **PCB Design with KiCad – updated for KiCad 9** (32 hours) — Udemy *(10/2026)*
- **Microcontroller Embedded C Programming: Absolute Beginners** — Udemy *(07/2026)*
- **Full Stack Web Development** — PNY Trainings, Lahore *(03–09/2024)*
- **Full Stack Web Development Bootcamp** — Udemy *(02–08/2024)*

---

## Languages

Urdu (native) · English (C1, fluent) · German (B2) · French (A1)

---

## Connect

<p align="center">
  <a href="https://github.com/majidkhan-dev"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="mailto:khanmajid.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://wa.me/923274403260"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
</p>
