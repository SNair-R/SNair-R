<p align="center">
  <img src="header.svg" alt="Sidharth Nair — Embedded firmware, Electrical Engineering at University of Houston" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sidharth-nair-"><img src="https://img.shields.io/badge/LinkedIn-0f1f2e?style=for-the-badge&logo=linkedin&logoColor=2dd4bf" alt="LinkedIn"></a>
  <a href="mailto:sidharthnair4306@gmail.com"><img src="https://img.shields.io/badge/Email-0f1f2e?style=for-the-badge&logo=gmail&logoColor=2dd4bf" alt="Email"></a>
  <a href="https://github.com/SNair-R/SNair-R/blob/main/Sidharth_Nair_Resume.pdf"><img src="https://img.shields.io/badge/Resume-2dd4bf?style=for-the-badge&logo=readthedocs&logoColor=0f1f2e" alt="Resume"></a>
</p>

I'm a BSEE student at the University of Houston (GPA 3.93, expected graduation May 2028) who writes embedded firmware in C/C++, from rover fault handling over CAN to small Pico builds that drive real displays, sensors and buzzers.

**Looking for Summer 2027 internships** in embedded, hardware, or controls (Houston or remote).

## Skills

![C](https://img.shields.io/badge/C-0f1f2e?style=flat-square&logo=c&logoColor=2dd4bf)
![C++](https://img.shields.io/badge/C++-0f1f2e?style=flat-square&logo=cplusplus&logoColor=2dd4bf)
![Python](https://img.shields.io/badge/Python-0f1f2e?style=flat-square&logo=python&logoColor=2dd4bf)
![MATLAB](https://img.shields.io/badge/MATLAB-0f1f2e?style=flat-square&logo=mathworks&logoColor=2dd4bf)
![Raspberry Pi Pico](https://img.shields.io/badge/Raspberry_Pi_Pico-0f1f2e?style=flat-square&logo=raspberrypi&logoColor=2dd4bf)
![Teensy 4.1](https://img.shields.io/badge/Teensy_4.1-0f1f2e?style=flat-square)
![NVIDIA Jetson](https://img.shields.io/badge/Jetson-0f1f2e?style=flat-square&logo=nvidia&logoColor=2dd4bf)
![CMake](https://img.shields.io/badge/CMake-0f1f2e?style=flat-square&logo=cmake&logoColor=2dd4bf)
![Git](https://img.shields.io/badge/Git-0f1f2e?style=flat-square&logo=git&logoColor=2dd4bf)
![Fusion 360](https://img.shields.io/badge/Fusion_360-0f1f2e?style=flat-square&logo=autodesk&logoColor=2dd4bf)

**Protocols & peripherals:** CAN 2.0B · I2C · PWM · ADC · GPIO

## Featured work

### [URC Rover Firmware](https://github.com/schradivarius/URC-MCU-Jetson-Comm-Protocol)
`C++` `CAN 2.0B` `Teensy 4.1` `Jetson`

Firmware team for a University Rover Challenge rover. My work is fault handling on the Teensy:

- Separate fault states for command-link loss and Jetson heartbeat loss, so autonomy keeps running through planned line-of-sight dropouts
- Heartbeat timeout and command-age checks on the 500 kbps CAN bus that drop stale drive commands and put the rover in a defined safe state
- Invalid-packet rejection, tested by injecting corrupted CAN frames
- Priority-ordered 11-bit message IDs so drive commands win arbitration over telemetry

### [PC Temperature Monitor](https://github.com/SNair-R/PC-Temp-Monitor)
`C` `Python` `Raspberry Pi Pico W` `I2C`

Live CPU/GPU temperature and usage on a 128x32 SSD1306 OLED, with overheat warnings. A Python host script streams stats over USB serial; the Pico parses them in C and draws them with a custom bitmap font.

### [Pomodoro Timer](https://github.com/SNair-R/Pomodoro-Timer)
`C` `Raspberry Pi Pico W` `I2C` `ADC` `PWM`

Standalone study timer with a 16x2 I2C LCD, potentiometer time selection, a debounced button and a PWM buzzer. Non-blocking millisecond timing keeps the UI responsive through a 4-cycle study/break session.

### Wafer Inspection *(in progress)*
`Python` `Computer vision`

Undergraduate research at Spark Up Research with a 3-person team building an automated wafer-inspection system. I'm developing the AI defect-detection model.
