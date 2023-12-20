# Automation Project using Timer and Counter

## Overview

This project, implemented on TIAPortal v15 using ladder diagram language, aims to control one pump and four valves with a single timer (TON) and a counter (CTU).

---

## Key Concepts

- **Memory Bit %M1.0:** Always ON throughout the process.
- **Memory Bit %M1.1:** Activated by %M1.0, triggering the timer.
- Timer resets after reaching one second, resetting %M1.1.
- The counter tracks seconds passed.
- Process stops when the counter reaches 100 seconds.

![Project Overview](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/0117c807-a8d4-43c7-adde-36384397872a)

---

## Code Structure

### Start and Stop Conditions

- **Start Condition:** 
  - Fill Button initiates the process.
 
- **Stop Conditions:** 
  - Discharge Button halts the process.
  - Counter reaches its maximum count.
 

![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/36fe8620-47ae-465a-8df3-1162e4418144)


### Additional Code Images

![Network Diagrams](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/663b81e4-0216-4d5f-b9f6-3c4b078cd3af)
- ![Code Image 1](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/4b621279-4422-4c53-be0f-598590872609)
- ![Code Image 2](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/69f83c34-c746-4b0b-9477-496a7aef07f3)
- ![Code Image 3](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/d9e08494-44fc-412c-8362-153800313f2c)
- ![Code Image 4](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/79a6bb60-90da-4794-9ca7-ae9e2881cd5a)
- ![WhatsApp Image 2023-06-14 at 8 16 07 AM](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/e4b99589-88e4-4138-a5f8-d359a2a637ff)

---

## Human-Machine Interface (HMI)

![HMI Interface](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/d7a9d688-08f1-4ce4-b037-546f18acf2c3)

