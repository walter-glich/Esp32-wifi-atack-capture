# ESP32 Management

> **Wireless management interface for ESP32**  
> A local web interface for configuring and launching ESP32 operations from a browser.

---

## ✨ Interface

The project provides a clean, mobile-friendly management panel that can be accessed from the ESP32's local network.

<p align="center">
  <img src="assets_readme/interface.jpeg" alt="ESP32 Management interface" width="360">
</p>

<p align="center">
  <em>Example of the ESP32 Management web interface</em>
</p>

---

## 🧩 Features

- 📡 **Wireless management** through a local web interface
- 🎯 **Target selection** from available networks
- ⚙️ **Operation configuration** from the browser
- 🔄 **Refresh networks** directly from the interface
- ⏱️ **Configurable timeout** for operations
- 🚀 **Start operation** with a single action
- 📱 **Responsive interface** designed to work comfortably from a phone

---

## 🖥️ Interface overview

### 🎯 Target selection

Choose the available target from the interface. The **Refresh networks** button lets you update the detected network list.

### ⚙️ Configuration

Configure the operation before starting it:

| Option | Description |
|---|---|
| **Operation type** | Select the operation to execute |
| **Operation method** | Select the available method |
| **Timeout** | Set the operation timeout in seconds |

### 🚀 Start operation

Once the configuration is ready, use **Start operation** to launch the selected operation.

---

## 🌐 Local interface

The management panel is intended to run locally on the ESP32.

Connect to the device's management access point and open the local interface in your browser.

```text
192.168.4.1
```

---

## 📁 Project structure

```text
.
├── README.md
└── assets_readme/
    └── interface.jpeg
```

---

## ⚠️ Documentation note

The uploaded `README.md` currently contains a **503 Backend.max_conn** error page instead of the project's original documentation. Because the original content was not available, this README is a polished replacement based on the interface shown in the provided screenshot.

If you provide the actual project README/source documentation, its original technical details can be incorporated into this layout.

---

<p align="center">
  <strong>ESP32 Management</strong><br>
  <sub>Wireless management interface</sub>
</p>
