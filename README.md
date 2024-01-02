# Arduino-Based Smart Light Project.

## 📚 Introduction.  
This project leverages the versatile Arduino Nano as the central control unit to process data and manage the connected components. The project features a pair of HC-SR04 ultrasonic sensors, a NE555 timer, a relay, a diode, two resistors (200k ohm and 10k ohm), two capacitors (22 micro F and 0.01 micro F), and a Common Cathode 7-Segment Display. The primary goal of this project is to measure distances in two distinct directions, visualize the results using a 7-segment display, and control an external load based on specific conditions. This comprehensive report offers an in-depth understanding of the project, its materials, working principles, and a conclusive summary.

## 🧰 Materials Used
- Arduino Nano
- HC-SR04 Ultrasonic Sensors (2)
- NE555 Timer
- Relay
- Diode
- Resistors (200k ohm and 10k ohm)
- Capacitors (22 micro F and 0.01 micro F)
- Common Cathode 7-Segment Display

## 🌐 Code and Schematic

![image](https://github.com/itheaks/iot-smartlight/assets/134759689/bcc46577-c891-4665-982e-bf0d6a19dd87)


- [Code Explanation](https://github.com/itheaks/iot-smartlight)
- Comprehensive wiring diagram or schematic for component connections.

## 📸 Illustrated Images


![image](https://github.com/itheaks/iot-smartlight/assets/134759689/4ab23fc3-18fb-484c-b367-3f82f0d397d9)


- Image 1: Project deactivating the relay and turning off the bulb.


![image](https://github.com/itheaks/iot-smartlight/assets/134759689/571d5a35-ea8a-408d-839f-b117260c4ea6)


- Image 2: Project activating the relay and turning on the bulb.

## 💻 Code Explanation
The Arduino code provided orchestrates the operation of the project and can be broken down into several critical components:
- **Library Inclusion and Variable Definitions:** `#include "SevSeg"` - Crucial for controlling the 7-segment display.
- **Setup Function:** `void setup()` - Initialization and pin configurations.
- **Loop Function:** `void loop()` - Main control logic and sensor measurements.

## ⚙️ Working
1. **Ultrasonic Sensor Measurements:** Measure distances in two directions.
2. **Timer and Other Sensor Inputs:** Read timer output and other sensor states.
3. **7-Segment Display:** Display variable 'i.'
4. **Relay Control:** Activate the relay based on 'i' and rear sensor distance.
5. **Control Logic:** Complex logic for 'i' and relay control.

## 📝 Conclusion
This project exemplifies a multifaceted system that harnesses the capabilities of the Arduino Nano in conjunction with a multitude of sensors and components. To offer a comprehensive understanding, a detailed wiring diagram would be invaluable. Furthermore, additional insights into the NE555 timer's role and connections would be indispensable to furnish a comprehensive perspective on the project. This endeavor provides valuable lessons for those interested in delving into the realm of Arduino-based control systems, sensor integration, and customization to cater to specific project requisites. There exists considerable room for refinement and customization to align the project with precise use cases and objectives.

For a more detailed explanation and the full code, visit the [GitHub Repository](https://github.com/itheaks/iot-smartlight).
