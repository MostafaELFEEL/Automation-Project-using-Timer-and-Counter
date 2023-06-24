# Automation-Project-using-Timer-and-Counter
## Idea
- The project was implemented on TIAPortal v15 using ladder diagram language. The main idea behind the project was to control one pump and four valves using only one timer (TON) and one counter (CTU).

- Memory bit %M1.0 is always ON during the whole process.

- Memory bit(%M1.1) is set by (%M1.0) which then activates the timer.

- Then the timer reaches timer value (one second) which resets memory bit %M1.1 (network 2 and network 3).

- Resetting (%M1.1) deactivates the timer which sets (%M1.1) repeating the process. 

- With this method we can count the number of seconds passing using a counter then condition all actuators on the counter value.

- The process will stop after counter reaches 100 (100 seconds).
![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/0117c807-a8d4-43c7-adde-36384397872a)

## Code
![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/36fe8620-47ae-465a-8df3-1162e4418144)

### First network is to setup the start and stop conditions of the process:
#### Start condition:
Fill: Button to start the process.
#### Stop condition:
Discharge: Button to stop the process.
Counter: Counter reaches max count.

![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/663b81e4-0216-4d5f-b9f6-3c4b078cd3af)
![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/4b621279-4422-4c53-be0f-598590872609)

![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/69f83c34-c746-4b0b-9477-496a7aef07f3)

![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/d9e08494-44fc-412c-8362-153800313f2c)

![image](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/79a6bb60-90da-4794-9ca7-ae9e2881cd5a)

![WhatsApp Image 2023-06-14 at 8 16 07 AM](https://github.com/MostafaELFEEL/Automation-Project-using-Timer-and-Counter/assets/106331831/e4b99589-88e4-4138-a5f8-d359a2a637ff)
