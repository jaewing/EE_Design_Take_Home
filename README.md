## Remote High Side Switch and Current Sensor Circuit Design Challenge

This repository contains all the KiCAD files and documentation to satisfy the design requirements outlined in the first two pages of the PDF titled "Main_Document" in the Documents folder. 

The circuit I designed solves the problem of turning on/off a load and reporting the current drawn by the load 100ft away from a PC in the conditions of an Airplane. To accomplish this the "Remote_RS485_Interface" circuit interfaces with the PC via USB and then communicates over RS485 the distance of 100ft of twisted pair wires to the "Local_RS485_Interface" circuit in which "ON/OFF" commands are sent to the High Side Switch to turn the load "ON" or "OFF". The "Local" interface communicates with the "Remote" interface via RS485 and reports "Current" measurements back to the Remote PC. 
![EE_Design_Challenge_Block_Diagram](https://github.com/jaewing/EE_Design_Take_Home/assets/134029402/d65a10d4-d5ab-4a68-a535-b4893453436d)
