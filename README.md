# CAN-bus-network-node

The main intent of this project was to develop a universal PCB which could be incorporated into any vehicle's instrumentation network inorder to provide CAN bus interface capability. The PCBSs will serve as nodes on the CAN bus. Each node will offer the following features :-
* An ESP32 microcontroller
* Precision ADC with matched front end having 8 analog inputs
* Wheel speed sensor interface
* Isolated CAN bus interface
* Isolated UART interface for debugging and diagnostics

## Block diagram of each node
![Image text](https://github.com/Xx-BHU1-xX/CAN-bus-network-node/blob/main/canNodeBlockDiagram.jpg)

ESP32 Devkit-V1 is being used as the main microcontroller. The board will serve as a carrier to utilize the in-built CAN controller of the ESP32 and to provide the features mentioned above. Schematics and the PCB was designed in KiCad 6.0. The main schematic has the following subsheets :-
* Power Distribution
* CAN
* Wheel speed
* Analog

Documentation for all sheets can be found in this repo
