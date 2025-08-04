# Arduino-UNO-Guitar-Shield

** This project is based on ElectroSmash's Arduino UNO Shield, all credit and 
similarities goes to them: https://www.electrosmash.com/pedalshield-uno **

This repository documents my personal recreation of the PedalSHIELD UNO project, an open-source programmable guitar pedal based on the Arduino UNO.

**The Primary Goal of This Project Is Educational:**
I undertook this build to deepen my understanding of PCB design and hardware manufacturing workflows. By reverse-engineering and rebuilding an existing open-source project, I aimed to:

* Learn the fundamentals of schematic capture and PCB layout.
* Gain hands-on experience with EDA tools and fabrication processes.
* Understand the practical challenges of bringing a hardware design from concept to physical board.
* Explore embedded audio processing using Arduino.

**This Repo Includes:**
* My custom PCB design files (schematics, layout, Gerbers).
* Notes and documentation on the design and manufacturing process.
* Photos and testing results from the assembled board.
* Reflections and lessons learned throughout the project.

**Personal Modifications and Reflections:**
While the core of this project was originally developed by ElectroSmash, I wanted to extend its functionality by integrating an OLED display to show the currently loaded effect on the Arduino. This small addition helped me explore how to interface displays with microcontrollers and consider user experience in hardware design.

**Design Improvements:** 
One key improvement I would make in a future revision is to increase the size of the copper pads. During assembly, I found that the small pad sizes made soldering more difficult—often resulting in cold joints or excessive solder use. Larger pads would improve solderability and make the process more forgiving and enjoyable. 

I'm also considering a Version 2.0 of the board that uses SMD components to reduce the overall footprint. Ideally, I’d like to integrate the OLED display directly onto the PCB for a more compact and professional design.

**What I Learned:**
This project was a deep dive into the end-to-end PCB design workflow. I spent a significant amount of time learning how to:

* Use KiCad 9 for schematic capture and PCB layout.
* Create custom symbols and footprints for components not found in the standard libraries.
* Select appropriate footprints (and learn the difference between THT and SMD).
* Troubleshoot issues like obsolete parts, incorrect footprints, and soldering challenges.

I encountered many real-world problems—such as not finding a footprint for a 3PDT switch and having to create one from scratch, or dealing with solder bridges and cold joints during assembly. These challenges taught me how to problem-solve independently, research effectively, and persist through trial and error.


![PCB Layout](https://github.com/user-attachments/assets/64b028d7-fed0-4b4b-ba33-3ed0487600c4)

![Full Schematic](https://github.com/user-attachments/assets/9fbe058b-4308-4460-aa3c-8c05dd3160ef)
