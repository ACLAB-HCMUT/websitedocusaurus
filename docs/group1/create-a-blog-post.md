---
sidebar_position: 3
---
# Installation and Operation
## Step-by-Step Installation:
---
### Preparation:

- Select an appropriately sized electrical cabinet.
- Ensure adequate length and gauge of electrical cables.
- Gather necessary installation tools such as screwdrivers, pliers, electrical tape, screws, and connectors.
  
### Install Modbus RTU Relay 32CH:

- Secure the relay module in the cabinet using screws or a DIN rail.
- Connect the 24V DC power source to the relay module’s power terminals.
- Connect the devices to be controlled to the relay channels according to the wiring diagram.
- Connect the RS485 port of the relay module to the Yolo Uno.
### Install Timer:

- Mount the Timer in the cabinet.
- Connect the 220V AC power source to the Timer’s power terminals.
- Connect the device to be controlled to the Timer’s output terminals.
- Set the on/off schedule as required.
### Install Circuit Breaker (Aptomat):

- Mount the circuit breaker, typically at the input of the system to protect the entire cabinet.
- Connect the 220V AC power source to the circuit breaker’s input terminals.
- Connect the circuit breaker’s output terminals to other devices or systems within the cabinet.
### Install Contactor:

- Secure the contactor in the cabinet.
- Connect the control power supply to the contactor’s coil terminals.
- Connect the load power supply to the contactor’s input terminals.
- Connect the device to be controlled to the contactor’s output terminals.
### Connect RS485:

- Connect the A and B lines of the RS485 from the Yolo Uno to the Modbus RTU Relay 32CH.
- Verify all connections are secure and free from faults.
### Program Yolo Uno:

- Install the appropriate development software, such as Arduino IDE.
- Write control programs using C++ to manage relay states via Modbus RTU.
- Upload the program to the Yolo Uno through the USB port.
- Test and fine-tune the program to ensure proper operation.
  
## Operation:
---
### Final Check:

- Ensure all connections are secure and correct.
- Power up the electrical cabinet and verify the functionality of each component.
### Monitoring and Maintenance:

- Regularly inspect and maintain the system to ensure stable and safe operation.