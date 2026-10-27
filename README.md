<h1 align="center">Hi, I'm Sidharth Nair 👋</h1>

<p align="center">
  Electrical Engineering student at the <b>University of Houston</b> building embedded systems, firmware, and custom hardware.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sidharth-nair-"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:sidharthnair4306@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/SNair-R/SNair-R/blob/main/Sidharth_Nair_Resume.pdf"><img src="https://img.shields.io/badge/Resume-111827?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume"></a>
</p>

---

## About me

- 🎓 BSEE student at the **University of Houston (Cullen College of Engineering)** · GPA 3.93 · Expected May 2028
- 🔧 Focused on **embedded systems**, **PCB design**, and low-level firmware in C/C++
- 🤖 **Firmware team** member on a University Rover Challenge (URC) rover
- 🔬 **Undergraduate researcher** at Spark Up Research (semiconductors & AI), developing an AI defect-detection model for an automated wafer-inspection system
- 🌱 Started in biology and switched to EE to build systems that help people; taught myself C/C++ and circuits before entering the major
- 🔭 Exploring **FPGA development** and **embedded security**
- 💼 Looking for **Summer 2027 internships** (Houston or remote) in embedded, hardware, and controls

## Tech stack

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi%20Pico-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion%20360-FF6B00?style=flat-square&logo=autodesk&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Hardware & protocols:** I2C · CAN 2.0B · PWM · ADC · GPIO · Teensy 4.1 · Jetson · Raspberry Pi Pico (RP2040, C SDK)
**Tools:** Git · GCC · Make · CMake · VS Code · Fusion 360 · schematic/PCB design (learning)

## Featured work

### 🔬 Wafer Inspection | Spark Up Research
Undergraduate researcher on a 3-person team (EE, mechanical, chemical engineering) building an automated wafer-inspection system. My part is developing the **AI defect-detection model**; the team is also converting a robotic arm to pick up and move wafers, and training on nanofab cleanroom processes to test on real wafers.

### 🤖 URC Rover Firmware | C++, Python, CAN, Teensy 4.1, Jetson
- Implemented fault handling that separates command-link loss from Jetson heartbeat loss, so autonomy keeps running through planned line-of-sight dropouts
- Added a Jetson heartbeat timeout and command-age checking over a 500 kbps CAN 2.0B bus, moving the rover to a defined safe state on stale commands
- Verified invalid-packet rejection by injecting corrupted CAN frames
- Prioritized drive commands over telemetry with priority-ordered 11-bit message IDs

### 🌡️ PC Temperature Monitor (Pico C SDK)
Desk display of live CPU/GPU temperature and usage on a 128x32 SSD1306 OLED, with warnings above 80°C / 85°C. A Python host script (WMI, psutil, nvidia-smi) streams data over USB serial; the Pico parses it in C and renders with a custom bitmap font over 100 kHz I2C.

### ⏱️ Pomodoro Timer (Pico C SDK)
16x2 I2C LCD, potentiometer, debounced buttons, and a PWM buzzer. Non-blocking millisecond timing keeps the display and buttons responsive through 60-minute sessions, driving a 4-cycle study/break state machine.

### 🎛️ Peripheral projects on the Pico
Potentiometer-controlled SG90 servo (PWM + calibration), SSD1306 OLED line-screen display, and an LCD 1602 over I2C. Along the way I debugged I2C bus/instance mismatches, ADC over-voltage from wiring mistakes, and multi-file CMake builds.

## Currently

- Contributing to rover firmware and wafer-handling research
- Working toward Summer 2027 embedded / hardware internships

## GitHub stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=SNair-R&show_icons=true&theme=transparent&hide_border=true&title_color=0A66C2&icon_color=0A66C2" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SNair-R&layout=compact&theme=transparent&hide_border=true&title_color=0A66C2" alt="Top languages" />
</p>

<p align="center"><i>Open to opportunities. Feel free to reach out!</i></p>
