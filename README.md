### **Keypad with STM32L010K4T6 MCU for Low-Power Input Interface**

This project features a compact and power-efficient **12-button keypad** designed to interface with a host PCB using **I2C** or **LPUART** communication protocols. At the core of the keypad is the **STM32L010K4T6** microcontroller, which manages button scanning, encoding, and communication to the host system. The keypad is optimized for low power consumption, entering **sleep mode** during periods of inactivity to conserve energy.

### **Key Features:**
- **12-Key Input**: A simple and intuitive interface for user input.
- **Low Power Design**: The STM32L010K4T6 MCU ensures low power operation, with the device entering sleep mode when not in use.
- **Flexible Communication**: Supports both **I2C** and **LPUART** for communication with the host PCB, allowing for versatility in system integration.
- **Efficient Host MCU Utilization**: By offloading the button scanning and key encoding to the STM32L010K4T6, the host MCU is freed from the processing load, enabling more efficient resource allocation and reduced CPU usage.
- **Compact and Modular**: The design is intended to be modular and reusable for various applications requiring user input in low-power environments.
- **Scalable**: Although this design features 12 buttons, the modular nature allows for easy adaptation to different input requirements.

### **Application Areas:**
- **Portable Devices**: Ideal for battery-powered systems that require a user interface without excessive power consumption.
- **Embedded Systems**: Can be integrated into a wide range of embedded systems where minimal user interaction is needed.
- **Low Power IoT Devices**: The keypad is particularly well-suited for Internet of Things (IoT) devices that demand low-energy solutions.

By using the **STM32L010K4T6 MCU** to manage the keypad’s input processing, this design reduces the workload on the host MCU, allowing it to focus on other critical tasks. This solution is ideal for applications where low power and efficient processing are key considerations.

Device Schematics:
![Alt text](https://github.com/phancak/Keypad-Board/blob/Allternate-Version-B/Keypad-Board-Schematics.png)
