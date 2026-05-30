# Turbojet
A miniature jet for desktop display


BOM:
| Qty | Item Description | Specification / Value | Source Reference |
|---|---|---|---|
| 1 | DC Motor | 3V - 6V Mini Hobby Type | Jet Turbine Core |
| 1 | LED Indicator | Standard 3mm or 5mm | Console Status Beacon |
| 1 | Fixed Resistor | 220-Ohm (\(\Omega\)) 1/4W | LED Protection |
| 10 | Fixed Resistors | 100-Ohm (\(\Omega\)) 1/4W | Speed Array Bundle |
| 3 | Slide Switches | SPDT 3-Pin Panel Mount | Power / Throttle Logic |
| 1 | Battery Enclosure | 3x AA or AAA Cell (4.5V) | Main Power Source |
| — | Hookup Wire | Solid Core / Stranded Gauge | Circuit Interconnects |

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
