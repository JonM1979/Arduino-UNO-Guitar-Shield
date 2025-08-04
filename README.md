# Conclusions and Demo

This project involved testing and evaluating several effects coded and shared by Electrosmash. While the signal generator worked as expected—with pushbuttons successfully changing the frequency—other effects such as fuzz, distortion, delay, and bit crusher did not perform as intended. These effects sounded overly harsh and loud, and the pushbuttons had little to no impact on their behavior.

To troubleshoot, I adjusted the potentiometer resistance, inspected and re-soldered questionable joints, and verified component values using a multimeter. I also used Electrosmash’s serial monitor code to confirm that the footswitch, pushbuttons, and guitar signal were all responding correctly. Despite these efforts, the issue persisted. I suspect a poor solder connection or a damaged component may be the root cause, possibly due to difficulties encountered during assembly.

Despite the technical challenges, this project was a valuable learning experience. I gained hands-on exposure to the full PCB design workflow—from schematic creation to board layout, manufacturing, and assembly. I also learned how component selection, footprint choice, and layout decisions can significantly impact the build process.

Before this project, I had no experience with PCB design beyond basic electrical concepts. I taught myself KiCAD through online resources and video tutorials. While the learning curve was steep, the process was incredibly rewarding. I’m grateful to the Electrosmash team for making their work open source, which provided a solid foundation and guidance throughout the project. I hope this inspires others to explore PCB design as well!


[![Watch the video](https://img.youtube.com/vi/rHayZxBrjfs/0.jpg)](https://www.youtube.com/watch?v=rHayZxBrjfs)

👉 [Watch the video on YouTube](https://www.youtube.com/watch?v=rHayZxBrjfs)


| Reference | QTY | Value | Description | Part ID |
| --- | --- | --- | --- | --- |
|C5,C2, C7, C8, C9| 5 | 6.8n | Ceramic Cap |  SR211C682MARTR1 |
| C3, C6, C10 | 3 | 4.7u | Electrolytic Cap | ECE-A1EKA4R7 |
| C1, C11 | 2 | 100n | Ceramic Cap |  SR211C104KARTR1 | 
| C4 | 1 | 270p | Ceramic Cap | D271K20Y5PH63L6R | 
| R12,R13, R10, R9, R6, R4, R3 | 7 | 4.7k | Resistor, 1%,1/4W | MFR-25FRF52-4K7 | 
| R5, R7, R8 | 3 | 100k | Resistor, 1%,1/4W | MFR-25FRF52-100K |
| R1, R2 | 2 | 1M | Resistor, 1%,1/4W | MFR-25FRF52-1M | 
| R11 | 1 | 1M2 | Resistor, 1%,1/4W | MFR-25FRF52-1M2 | 
| RV1 | 1 | 500k | resistor trimmer | PV36W504C01B00 | 
| D1 | 1 | LED 3mm Blue | LED | SSL-LX3044USBC | 
| U1 | 1 | TL972 pdip-8 | op-amp rail-to-rail | TL972IP | 
| IC Socket | 1 | dip 8 socket | socket for dip8 | 1-2199298-2 |
| SW1, SW2 | 2 | Pushbutton | off-on pushbutton | R13-24A-05-WH-B |
| SWITCH_3PDT | 1 | 3DPT | 3DPT | SF17020F-0302-21R-L-015 | 
| SWITCH_INV | 1 | Toggle Switch | SPDT Toggle Switch | 100SP1T1B1M1QEH | 
| Connector Pins | 1 | 40 Pin Header | 2.54 Pitch Pin Header | 710-61304011121 | 
| Input, Output Jack | 2 | 1/4 Audio Jack | Stereo 6.35mm Jack | NMJ6HCD2 | 
