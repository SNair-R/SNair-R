# Sidharth Nair

Electrical Engineering student at the University of Houston (BSEE, GPA 3.93, expected May 2028). I write embedded firmware in C/C++: rover fault handling over CAN, and small Pico projects that drive real displays, sensors and buzzers.

[LinkedIn](https://www.linkedin.com/in/sidharth-nair-) · [Email](mailto:sidharthnair4306@gmail.com) · [Resume](https://github.com/SNair-R/SNair-R/blob/main/Sidharth_Nair_Resume.pdf)

Looking for Summer 2027 internships in embedded, hardware, or controls (Houston or remote).

---

### [URC Rover Firmware](https://github.com/schradivarius/URC-MCU-Jetson-Comm-Protocol)
C++ · CAN 2.0B · Teensy 4.1 · Jetson

Firmware team for the University of Houston's University Rover Challenge rover. My work is fault handling on the Teensy:

- Separate fault states for command-link loss and Jetson heartbeat loss, so autonomy keeps running through planned line-of-sight dropouts
- Heartbeat timeout and command-age checks on the 500 kbps CAN bus that drop stale drive commands and put the rover in a defined safe state
- Invalid-packet rejection, tested by injecting corrupted CAN frames
- Priority-ordered 11-bit message IDs so drive commands win arbitration over telemetry

### [PC Temperature Monitor](https://github.com/SNair-R/PC-Temp-Monitor)
C · Python · Raspberry Pi Pico W · I2C

Live CPU/GPU temperature and usage on a 128x32 SSD1306 OLED, with overheat warnings. A Python host script streams stats over USB serial; the Pico parses them in C and draws them with a custom bitmap font.

### [Pomodoro Timer](https://github.com/SNair-R/Pomodoro-Timer)
C · Raspberry Pi Pico W · I2C · ADC · PWM

Standalone study timer with a 16x2 I2C LCD, potentiometer time selection, a debounced button and a PWM buzzer. Non-blocking millisecond timing keeps the UI responsive through a 4-cycle study/break session.

### Wafer Inspection (in progress)
Python · computer vision

Undergraduate research at Spark Up Research with a 3-person team building an automated wafer-inspection system. I'm developing the AI defect-detection model.

---

**Languages:** C, C++, Python, MATLAB  
**Embedded:** I2C, CAN, PWM, ADC, GPIO · Raspberry Pi Pico (RP2040, C SDK), Teensy 4.1, Jetson  
**Tools:** Git, GCC, Make, CMake, VS Code, Fusion 360

Before EE I was a biology major; I taught myself C/C++ and circuits to make the switch.
