# 📈 Portable Oscilloscope using Raspberry Pi Pico

A low-cost, portable oscilloscope and logic analyzer designed to work with Android devices using Raspberry Pi Pico and the **Scoppy** application.

---

## 🎯 Aim

Design and build an affordable, user-friendly oscilloscope and logic analyzer that interfaces seamlessly with Android smartphones/tablets, powered by **Raspberry Pi Pico**.


<p align="center">
  <img src="https://github.com/user-attachments/assets/16df3a6b-0cf7-4f12-a24b-eed161aeac81" width="500" alt="Connection Diagram"/>
  <br>
  <b>Figure 1:</b> Bulky and Costly Oscilloscope
</p>


---

## 🧠 Theory

The **Raspberry Pi Pico** is a powerful yet budget-friendly microcontroller board built around the RP2040 chip, making it ideal for electronics projects, robotics, and IoT applications. Its combination of **dual-core ARM Cortex-M0+ processors**, **264KB RAM**, and extensive I/O capabilities allows it to handle real-time signal processing tasks like waveform capture for oscilloscope functionalities.

---

## 🔩 Raspberry Pi Pico Key Specifications

- RP2040 Microcontroller with **Dual-core ARM Cortex-M0+** @ 133MHz
- **264KB on-chip SRAM**
- **26 GPIO pins**, including:
  - 3 ADC pins (Analog to Digital Converter)
  - 2 SPI pins
  - 2 I2C pins
  - 3 UART pins
- **Programmable I/O (PIO)** for flexible peripherals
- **12-bit DAC** via analog comparator
- **Free SDK** for C/C++ development
- **Low power consumption**
- **Compact size:** 25.4mm × 21.4mm
- **Ultra-affordable** for students and hobbyists

---

## 📱 Scoppy Application Overview

**Scoppy** is an oscilloscope and logic analyzer app that works with your Android device and Raspberry Pi Pico (or Pico W).

- **How it works:** 
  - Signals are measured by the Raspberry Pi Pico.
  - Waveforms are displayed in real time on your Android phone or tablet via the Scoppy app.
- **No programming required:** Both the app and firmware are freely available.
- **Easy installation:** Setup takes only a few minutes.

### 📡 Pico W Advantage
The **Pico W** (Wi-Fi enabled version) lets you use Scoppy **wirelessly**, eliminating the need for a physical USB connection between the Pico and your smartphone.

---

## 🚀 Why Raspberry Pi Pico for Scoppy?

- **Affordability:** Accessible even to beginners and students.
- **Versatility:** Can be used for a variety of projects beyond oscilloscope tasks.
- **Built-in ADC:** Enables capturing and digitizing of analog signals crucial for waveform visualization.
- **Compact Design:** Easy to integrate into portable systems.
- **Wide Support:** Rich community, documentation, and SDKs.

---

## ⚡ Features of Scoppy + Raspberry Pi Pico Setup

- Oscilloscope Mode:
  - View analog waveforms (low voltage, low frequency)
- Logic Analyzer Mode:
  - Sample rate up to **25MS/s** for digital signals
- Touch-friendly interface via Android device
- Ultra-portable and ultra-low cost
- Free app and firmware support

---

## 🛠️ Installation and Usage (Quick Overview)

1. Flash the Scoppy firmware onto your Raspberry Pi Pico/Pico W.
2. Install the **Scoppy** app from the Google Play Store.
3. Connect the Pico to your Android device (via OTG cable or Wi-Fi for Pico W).
4. Launch the app and start measuring signals instantly.

---

## Results.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3de35a8f-eb9e-422a-b750-9e8687867e9d"/>
  <br>
  <b>Figure 2:</b> Rectangular Waveform
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/59c99c54-5dd9-455b-97e1-a2ad863eaaf0" width="500" alt="Connection Diagram"/>
  <br>
  <b>Figure 3:</b> Sinusoidal Waveform
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/5391c93d-8fbe-4e1a-ba68-6a3f5c44ac1f" width="500" alt="Connection Diagram"/>
  <br>
  <b>Figure 4:</b> Triangular Waveform
</p>

---

## 📚 References

- [Scoppy Official Website](https://www.scoppy.io/)
- [Raspberry Pi Pico Documentation](https://www.raspberrypi.com/documentation/microcontrollers/)
- [Scoppy GitHub Repository](https://github.com/paulhamsh/scoppy)

---

> 📌 *This project aims to democratize access to oscilloscope and logic analyzer tools, making electronics learning more affordable, accessible, and portable.*

