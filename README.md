# Embedded Systems & IoT Portfolio

A curated collection of hands-on projects and laboratories from my University course in Embedded Systems. This portfolio demonstrates practical implementation of firmware development, communication protocols, driver design, and PCB creation—with a focus on autonomous systems like the Micromouse.

## 🛠 Technical Skills Demonstrated
*   **Programming Languages:** C, C++, Python
*   **Microcontroller:** STM32F411 
*   **Communication Protocols:** UART, I2C, SPI, Infrared (IR)
*   **Tools & Software:** STM32CubeIDE, KiCad (PCB Design), Oscilloscope, Logic Analyzer, Circuits
*   **Core Concepts:** Interrupt Service Routines (ISR), Peripheral Drivers, Sensor Integration, Real-Time Systems, Motor Control

## 📁 Project Highlights

### Project 1: Infrared (IR) Communication Protocol Decoder
*   **Objective:** Reverse-engineer and decode the protocol of a standard IR remote control.
*   **Implementation:** Developed a program in C to capture, timing, and interpret the digital signals transmitted by the remote for each key press. Decoded data was displayed visually using LEDs, representing the binary code of each key.
*   **Key Achievement:** Successfully mapped the entire button set of a remote to their unique binary codes, creating a reusable IR decoding library.

### Project 2: DC Motor Control System with Interrupts
*   **Objective:** Create a responsive system to precisely control the speed of a DC motor and measure its performance metrics.
*   **Implementation:** Utilized the previously developed IR decoder as an input method for control commands. Implemented **Interrupt Service Routines (ISRs)** for accurate timing to measure motor speed (RPM) and response times, ensuring real-time performance.
*   **Key Achievement:** Built a closed-loop control system that demonstrated the critical role of interrupts in handling time-sensitive hardware interactions.

## 📜 Repository Structure
Each laboratory folder contains its complete source code, detailed documentation, schematics,
