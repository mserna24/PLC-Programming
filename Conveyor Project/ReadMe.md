# Conveyor Belt PLC Program
## PLC Code Purpose
The following PLC code is written in RSLogix 500 for the purpose of operating a conveyor system. 
The conveyor contains two hoppers that open to dispense material when their respective photoelectric 
sensors are triggered. Simultaneously, the proximity switch criteria must be met before the hoppers can open. 
After a set amount of time, a level switch is triggered to continue the conveyor cycle, concluding one complete 
cycle of operation.
## List of Inputs and Outputs (I/O)
### Inputs
- Proximity Switch
- Level Switch
- Red Photoelectric sensor
- Blue Photoelectric sensor
### Outputs
- Conveyor Motor
- Walnut Hopper
- Pecan Hopper

## Instructors Used
- Energize If Closed (XIC)
- Energize If Open (XIO)
- One Shots (ONS)
- Output Energized (OTE)
- Timer On Delay (TON)

### Files (3 Files)
- LAD 2 - Main
- LAD 3 - Inputs
- LAD 4 - Outputs
- LAD 5 - Controls
