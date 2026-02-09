# << ## **ESP8266 Wireless IMU Node (PCB Design) 📡** ## >>

***

### << ## **📋 Project Summary (Overview)** ## >>
***

** **This project is a battery-powered, compact, and independent Wireless Motion Sensor node designed for IoT (Internet of Things) applications.**
** **The board reads acceleration and gyroscope data through the onboard MPU-6050 sensor and transmits it to a Wi-Fi network (MQTT, TCP/UDP, etc.) via the ESP8266 (ESP-12F) module.**
** **It features an internal Boost Converter circuit to allow operation from a single battery cell.**

---

### << ## **🛠️ Technical Specifications** ## >>

| Feature | Detail |
| :--- | :--- |
| **Microcontroller** | ESP-12F (ESP8266 Wi-Fi SoC) |
| **Sensor** | MPU-6050 (3-Axis Accelerometer + 3-Axis Gyroscope) |
| **Power Source** | 1x AA or Li-Ion Battery Cell |
| **Power Management** | **MCP1640** Boost Converter (Generates 3.3V from 0.8V input) |
| **User Interface** | 1x Programmable Button, 2x Status LEDs |
| **Antenna** | On-board PCB antenna (Keep-out zone design applied) |
| **Design Tool** | KiCad EDA |



---

### << ## **📸 Design Gallery** ## >>

#### << ## **1. 3D Render** ## >>
** **A 3D render of the final board assembly. The placement of the battery holder and the ESP module has been optimized for size.**

![3D View](assets/pcb-3d-top-view.jpg)

#### << ## **2. PCB Layout & Routing** ## >>
** **A dual-layer (2-Layer) design. "Keep-out" areas were strictly maintained in the RF (Antenna) section to ensure signal integrity.**
** **Power planes were kept wide to minimize electrical noise during transmission.**

![PCB Layout](assets/pcb-layout-routing.jpg)

#### << ## **3. Schematic Diagram** ## >>
** **The circuit schematic illustrating the power management stage and sensor connections.**

![Schematic](assets/schematic-diagram.jpg)



---

### << ## **🚀 Use Cases** ## >>
** **Remote vibration analysis (Machine health monitoring).**
** **Wearable technologies (Pedometer, fall detection).**
** **Wireless sensor module for robotics projects.**
** **Smart home automation triggers.**

---

**License:** MIT License
