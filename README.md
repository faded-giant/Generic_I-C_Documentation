# Generic_I-C_Documentation

# 📟 Board Pinout Documentation

This document provides an overview of the **pin assignments** for the Arduino **12 slots** Breakout, each slot has a **4-pin power header at the top**, and a **6-pin communication header at the bottom**. The pin numbers listed below correspond to the **Arduino Mega** pin mappings, which can be used directly in **Arduino code**.
![image](https://github.com/user-attachments/assets/bf6460d9-afe8-4721-8198-74e17c5c6802)

Power Applied to J1 is connected to each slot's power header. a 5VDC regulator provides power to the Arduino and the communication headers. 
---

## 🛠️ Slot Pin Assignments

Each slot has a dedicated **analog** and **digital** pin. These pins correspond to the **Arduino Mega's headers** and can be referenced in **Arduino sketches**.

| Slot | Analog Pin | Digital Pin |
|------|-----------|-------------|
|  1   | A0        | 22          |
|  2   | A1        | 23          |
|  3   | A2        | 24          |
|  4   | A3        | 25          |
|  5   | A4        | 26          |
|  6   | A5        | 27          |
|  7   | A6        | 28          |
|  8   | A7        | 29          |
|  9   | A8        | 30          |
| 10   | A9        | 31          |
| 11   | A10       | 32          |
| 12   | A11       | 33          |

---

## 🔌 Headers

### **Top 2-Pin Header (Power)**
The **4-pin power header** at the top of the board connects to the **Arduino Mega's power pins**.

[PWR] [GND]

### **Bottom 6-Pin Header (Communication & Power)**
The **6-pin header** at the bottom provides power and communication connections, wired to the respective **Arduino Mega** pins.
[GND] [VCC] [TX] [RX] [SCL] [SDA]

### 📌 Notes:
- The **digital pins** listed above can be used directly in **Arduino sketches** (e.g., `digitalWrite(22, HIGH);`).
- The **analog pins** (A0–A11) are available for reading sensors or other inputs (`analogRead(A0);`).
- The **headers are directly connected** to the respective Arduino Mega pins for ease of wiring.
