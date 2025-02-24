# Generic_I-C_Documentation

# 📟 Board Pinout Documentation

This document provides an overview of the **pin assignments** for the Arduino **12 slots** Breakout, each slot has a **4-pin power header at the top**, and a **6-pin communication header at the bottom**. The pin numbers listed below correspond to the **Arduino Mega** pin mappings, which can be used directly in **Arduino code**.
![image](https://github.com/user-attachments/assets/bf6460d9-afe8-4721-8198-74e17c5c6802)

Power Applied to J1 is connected to each slot's power header. a 5VDC regulator provides power to the Arduino and the communication headers. 

A I2C Header is provided for an LCD screen

DIO pins 1-8 have breakout pins next to a GND pin for digital inputs. Facing the board, the GND pin is the left pin, and the DIO pin is the right.

---

## 🛠️ Slot Pin Assignments

Each slot has a dedicated **analog** and **digital** pin. These pins correspond to the **Arduino Mega's headers** and can be referenced in **Arduino sketches**.

| Slot | Analog Pin | Digital Pin |
|------|-----------|-------------|
|  1   | A1        | 22          |
|  2   | A2        | 23          |
|  3   | A3        | 24          |
|  4   | A4        | 25          |
|  5   | A5        | 27          |
|  6   | A6        | 26          |
|  7   | A7        | 28          |
|  8   | A8        | 29          |
|  9   | A9        | 30          |
| 10   | A10        |11          |
| 11   | A11       | 12          |
| 12   | A12       | 13          |

---

## 🔌 Headers

### **Top 4-Pin Header (Power)**
The **4-pin power header** at the top of the board connects to the **Arduino Mega's power pins**.

 [GND] [GND] [PWR] [PWR]

### **Bottom 6-Pin Header (Communication & Power)**
The **6-pin header** at the bottom provides power and communication connections, wired to the respective **Arduino Mega** pins.
The pins for each slot are oriented (with front facing you) as follows:
[GND] [DIO] [AIO] [SCL] [SDA] [5V]

### 📌 Notes:
- The **digital pins** listed above can be used directly in **Arduino sketches** (e.g., `digitalWrite(22, HIGH);`).
- The **analog pins** (A0–A11) are available for reading sensors or other inputs (`analogRead(A0);`).

