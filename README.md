<div align="center">
  <h1>🏠 eWeLink Desktop (Sonoff PC Client)</h1>
  <p><b>Fast, Modern, and Powerful Desktop Client for eWeLink Smart Home Devices</b></p>
  
  [![Release](https://img.shields.io/github/v/release/Mrserg123/ewelink-react-update?style=flat-square)](https://github.com/Mrserg123/ewelink-react-update/releases)
  [![Downloads](https://img.shields.io/github/downloads/Mrserg123/ewelink-react-update/total?style=flat-square)](https://github.com/Mrserg123/ewelink-react-update/releases)
  [![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=flat-square)](#)
</div>

---

**eWeLink Desktop** is a third-party, feature-rich desktop application built for managing your smart home. Control your Sonoff devices, check power monitoring stats, and manage groups directly from your Windows or Linux PC without taking your smartphone out of your pocket!

Built on a modern **Electron + React** stack, it provides real-time WebSocket updates, multi-language support, and a sleek user interface.

[🇷🇺 Читать описание на Русском (Russian Description)](#-описание-на-русском)

## ✨ Key Features

- ⚡ **Real-Time Control (WebSockets):** Instant synchronization with your devices. Toggle a switch on your phone, and it updates immediately on your PC.
- 🔌 **Power Monitoring:** Dedicated page to view real-time energy consumption, voltage, and current for supported devices (e.g., Sonoff POW).
- 🌍 **Smart Regional Routing:** Automatically detects your eWeLink account region (EU, US, AS, CN) and connects to the correct server.
- 🎨 **Customizable Themes:** Switch between sleek Dark and Light modes.
- 🌐 **Multi-language Support:** Interface available in English, Russian (RU), Ukrainian (UA), and Polish (PL).
- 🔄 **Seamless Auto-Updates:** Built-in auto-updater so you'll never miss a new feature.
- 🏠 **Families & Rooms Management:** Organize your devices exactly as they are in the mobile app.

---

## 📥 Installation

1. Go to the [Releases Page](https://github.com/Mrserg123/ewelink-react-update/releases).
2. Download the installer for your OS:
   - **Windows:** Download `eWelink-Setup-X.X.X.exe`
   - **Linux:** Download `ewelinkv2-X.X.X.tar.gz`
3. Run the installer and log in with your standard eWeLink credentials!

---

## 🛠 Tech Stack

- **Core**: Electron, React, Node.js
- **Build Tools**: Webpack 5, Electron-Builder
- **UI Framework**: Ant Design
- **State Management**: Redux Toolkit
- **Routing**: React Router DOM v6
- **I18n**: i18next
- **API Wrapper**: ewelink-api (v2)

---

## 🇷🇺 Описание на Русском

**eWeLink Desktop** — это удобный и современный клиент для управления умным домом eWeLink (Sonoff и совместимые устройства) прямо с вашего компьютера на базе Windows или Linux.

Приложение напрямую взаимодействует с официальным API eWeLink и поддерживает мгновенное обновление статусов через WebSockets.

**Главные фичи:**
- **Мониторинг энергии (Power Monitoring):** Просматривайте напряжение, силу тока и потребленную энергию ваших приборов.
- **Мгновенный отклик:** Включаете свет со смартфона — статус на ПК обновляется моментально.
- **Умная авторизация:** Клиент сам определит ваш регион (EU, US, AS, CN).
- **Сворачивание в трей:** Программа аккуратно работает в фоне, не мешая вашей работе.
- **Темы и Языки:** Темная/Светлая тема, а также Русский и Украинский языки «из коробки».

Для установки просто перейдите в [Релизы](https://github.com/Mrserg123/ewelink-react-update/releases) и скачайте последний файл `.exe`.

---
*Disclaimer: This is a community-driven project and is not officially affiliated with CoolKit or eWeLink.*
