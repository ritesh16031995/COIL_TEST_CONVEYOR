# COIL TESTING CONVEYOR – Omron PLC & HMI Automation

## Project Overview
The **Coil Testing Conveyor** is an industrial automation project designed to automate the electrical testing and assembly process of coils using an Omron PLC and HMI.
The system integrates a Kikusui TOS5200 Withstanding Voltage Tester and a Hioki RM3544 Resistance Meter with the PLC to perform automated electrical testing, acquire test results, and execute subsequent assembly operations based on OK/NG judgment.
The project combines automated testing, conveyor control, and assembly sequencing to achieve a controlled and repeatable manufacturing process.

## Key Features
- Omron PLC-based machine sequence and control logic development.
- HMI development for machine operation, monitoring, and status indication.
- Communication integration with Kikusui TOS5200 Withstanding Voltage Tester.
- Communication integration with Hioki RM3544 Resistance Meter.
- Automated electrical testing and OK/NG result processing.
- Automatic clipping and screwing operations based on electrical test results.
- Sequence interlocking and process control for reliable machine operation.
- Integration of testing and assembly operations into a single automated cycle.

## System Components
| Component | Function |
|---|---|
| Omron PLC | Machine sequence control and automation logic |
| Omron HMI | Operator interface, machine status, and process monitoring |
| Kikusui TOS5200 | Withstanding voltage testing |
| Hioki RM3544 | Resistance measurement |
| Conveyor System | Workpiece transfer between process stations |
| Clipping Mechanism | Automated coil clipping operation |
| Screwing Mechanism | Automated screw fastening operation |

## Working Principle
The machine operates through a sequence of automated testing and assembly operations.

1. **Workpiece Loading and Positioning**  
   The coil is transferred through the conveyor system and positioned at the designated testing station.

2. **Electrical Testing**  
   The Omron PLC communicates with the Kikusui TOS5200 and Hioki RM3544 to execute the required electrical tests and acquire the measurement results.

3. **OK/NG Judgment**  
   The PLC processes the received test results and determines whether the coil meets the defined acceptance criteria.

4. **Automated Clipping and Screwing**  
   The PLC executes the clipping and screwing sequence according to the test judgment. The assembly sequence is permitted for OK products, while NG products are prevented from proceeding through the normal assembly sequence.

5. **Process Completion**  
   The machine completes the programmed sequence and prepares for the next workpiece.

## My Contribution
- Developed Omron PLC ladder logic for automated machine sequencing, conveyor control, and process interlocking.
- Designed and developed HMI screens for machine operation, status monitoring, and process control.
- Integrated PLC communication with Kikusui TOS5200 and Hioki RM3544 for automated electrical testing and test result acquisition.
- Implemented OK/NG judgment logic and automated clipping and screwing sequences based on electrical test results.
- Developed coordinated testing and assembly logic to achieve a repeatable and controlled production cycle.

## Technologies Used
- Omron PLC Programming
- Omron HMI Development
- Industrial Instrument Communication
- Electrical Testing Automation
- Conveyor Automation
- OK/NG Inspection Logic
- Automated Assembly Control

## Project Objective
To develop an integrated PLC-based automation solution that combines electrical testing, result-based decision-making, conveyor handling, and automated assembly operations, improving process consistency and reducing manual intervention.

## Author
RITESH
