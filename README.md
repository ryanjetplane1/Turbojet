# Turbojet
<img width="1141" height="983" alt="image" src="https://github.com/user-attachments/assets/03874afa-4345-42aa-a18f-28b39d45579c" />

A miniature control panel for a 3D printed jet engine that lets you toggle between thrust modes. This project was made as a simple hardware build using spare parts bypassing the need for a microcontrollers. The jet runs on a 4.5V battery pack and features 3 control switches. Features include a master power switch, a dedicated status LED, a 50 percent thrust toggle, and a 100 percent full throttle bypass switch. Control is very easy flip Switch 1 to arm the system and turn on the status LED, flip Switch 1 to run at a 50 percent power, and flip Switch 2 while switch 1 is on to run at 100 percent power. 


BOM:


| Qty | Item Description | Specification / Value | USD | Link |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Motor/Battery/Wires | 3V to 12V DC hobby kit | 11.99 | https://amazon.com |
| 1 | LED Indicator | Standard 6mm Power Status LED | 9.99 | https://amazon.com |
| 1 | Slide Switches | SPDT 3 Pin Panel Mount | 13.99 | https://amazon.com |
| 1 | Solder | Holds wires | 8.99 | https://amazon.com |
| **Total** | | | **$44.96** | |




Wiring:
Resistor bundle is ten 100 Ohm resistors wired together in parallel.

Step 1: Main Input
Connect Battery Positive to Switch 1 Middle Pin.

Step 2: Power Indicator
Connect Switch 1 Right Pin to a 220-Ohm resistor.
Connect the other side of that resistor to the LED Long Leg (+).
Connect the LED Short Leg (-) to Battery Negative.

Step 3: Speed Switch
Connect Switch 1 Right Pin to Switch A Middle Pin.
Connect Switch 1 Right Pin to Switch B Middle Pin.

Step 4: 50% Speed 
Connect Switch A Right Pin to the Left side of the 10 Resistor Bundle.
Connect the Right side of the 10 Resistor Bundle to Motor Positive.

Step 5: 100% Speed 
Connect Switch B Right Pin straight to Motor Positive.

Step 6: Ground Path
Connect Motor Negative straight to Battery Negative.

<img width="1802" height="1480" alt="image" src="https://github.com/user-attachments/assets/acc54919-ec0e-4f00-85f3-74bf21b8bbd3" />


F3D files can be found in the releases section.
