# LCD Name Display with LED Indicators - Jetson Nano

This project was developed for **EEE 313 - Introduction to Embedded Systems**. It features an interactive LCD and LED system using the **NVIDIA Jetson Nano Developer Kit**.

**[Watch Project Video](https://youtu.be/YsNNwLQHaM0?feature=shared)**

---

## Purpose

To build an embedded system that:
- Displays team members’ names on a 16x2 LCD screen
- Activates different LEDs depending on which line the name is shown
- Demonstrates real-time interaction and visual feedback using LEDs

---

## Hardware Components

- NVIDIA Jetson Nano Developer Kit  
- 16x2 LCD Display (I2C or Parallel)
- 2x LEDs (Red and Green)
- Breadboard, jumper wires, resistors

---

## Project Features

- **LCD Name Display**: Shows names “Suat” and “Ata” on the LCD
- **LED 1 (Red)**: Lights up when a name is displayed on the **first line**
- **LED 2 (Green)**: Lights up when a name is displayed on the **second line**
- **Jetson Nano**: Acts as the control center via Python GPIO
- **Real-Time Feedback**: LEDs provide immediate visual confirmation

---

## GPIO Pin Mapping

| Component        | GPIO Pin |
|------------------|----------|
| LCD (Data/Control Pins) | (Defined per library or I2C address) |
| LED 1 (Red)      | Custom (e.g., GPIO 13) |
| LED 2 (Green)    | Custom (e.g., GPIO 7)  |

Exact wiring can be found in the Fritzing file.

---

## Software

- **IDE**: Thonny
- **Language**: Python 3
- **Library**: Jetson.GPIO + any LCD library (I2C or direct GPIO)

---

## 🧾 File Structure

├── Code_LCD_screen.py # Main Python script

├── jetson_finder_schmetics_lcd_screen.fzz # Fritzing circuit

├── Application Homework-3.docx # Homework documentation


---

## 📷 Circuit Diagram

- See [`jetson_finder_schmetics_lcd_screen.fzz`](jetson_finder_schmetics_lcd_screen.fzz)
- Built using **Fritzing**

---

## 🧑‍🤝‍🧑 Team Members

- **Suat Deniz**
- **Ata Güneş**

---

## ⚖️ License

This project is licensed under the **MIT License**.


---

## 🧠 Notes

- Jetson Nano-specific code with Jetson.GPIO
- Arduino IDE **not used**, compliant with course restrictions
- Designed for physical demonstration only (no simulation involved)

