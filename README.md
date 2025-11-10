# 🤲 Automatic Hand Dryer System

This project was developed for the **Embedded System** course by **Wina Sorta Maria Gea** — Institut Teknologi Del.  
The system uses an **ultrasonic sensor** to detect hands and automatically activate an **8V DC fan** through a relay.  
It is also equipped with an LED and a buzzer as visual and audio indicators.

---

## ⚙️ Components
- Arduino UNO  
- Ultrasonic Sensor HC-SR04  
- 1-Channel Relay Module  
- 8V DC Fan  
- Male & Female DC Jack  
- LED + 220Ω Resistor  
- Buzzer  
- 8–12V DC Power Supply  

---

## 🧠 Working Principle
1. The ultrasonic sensor measures the distance to detect a nearby hand.  
2. When a hand is detected at less than 15 cm, the relay is activated and the fan turns on.  
3. The LED lights up and the buzzer sounds as indicators.  
4. When the hand is removed, all components automatically turn off.  

---

## 🧾 Main Code
See the main code file in the folder: [`Code/HandDryer.ino`](Code/HandDryer.ino)

---

## 📸 Documentation

The following images show the complete design, schematic, implementation, and testing process of the project:

- [`Images/Desain_Perancangan_Sistem.jpg`](Images/Desain_Perancangan_Sistem.jpg) – System design overview showing the main concept and component interaction.  
- [`Images/Desain_Skematik.jpgg`](Images/Desain_Skematik.jpg) – Electronic schematic illustrating connections between Arduino UNO, ultrasonic sensor, relay, LED, buzzer, and fan.  
- [`Images/Flowchart.jpg`](Images/Flowchart.jpg) – Flowchart showing the logical process of the automatic hand dryer operation.  
- [`Images/Implementasi_Hardware_Front.jpg`](Images/Implementasi_Hardware_Front.jpg) – Front view of the hardware implementation.  
- [`Images/Implementasi_Hardware_Under.jpg`](Images/Implementasi_Hardware_Under.jpg) – Bottom view of the hardware wiring and layout.  
- [`Images/Pengujian Hardware.jpg`](Images/Pengujian Hardware.jpg) – Hardware testing results and performance visualization.



---

## 👩‍💻 Author
**Wina Sorta Maria Gea**  
Computer Technology — Institut Teknologi Del  
📍 Laguboti, Toba, North Sumatra, Indonesia  

---

## 👥 Collaboration
This project was developed as a **team project** for the *Embedded System* course  
at **Institut Teknologi Del**.  

I contributed to Arduino programming, system design, documentation and partly helped with hardware setup.
---

## 🏷️ License
This project is licensed under the [MIT License](LICENSE).

