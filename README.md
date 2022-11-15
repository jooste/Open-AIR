# Open_Air

Open AIR is an open source system for home ventilation and control via Home Assistant. The goal of this project is to create an eco system of Open Source and Home Assistant compatible devices that can be installed in a wide variaty of ventilation devices.

The Open AIR system must be able to do the following:
 - Measure huidity in an air duct.
 - Measure CO2 in an air duct
 - Measure tmperature in an air duct
 - Be WiFi enabled by default
 - Be fully controllable by Home Assistant out of the box
 - Be Open Source

The long term goal for this project is create a completely Open Source venilation box which can be 3D printed (preferrably out of recycled plastic).

#### Open AIR Mini:
The Open AIR Mini is an Open Source controller that works with at least the following ventilation boxes:
- DucoBox Silent Standard
- DucoBox Silent Perilex
- DucoBox Silent Connect
- DucoBox Focus (⚠ Warning: Original Duco Valves are not supported! ⚠)
- Orcon MVS-15RH

For more information about the Open AIR Mini see: [Open AIR Mini](https://github.com/Flamingo-tech/Open-AIR/tree/main/Open%20Air%20Mini) 

#### Open AIR Valve:
The Open AIR Valve is a open source valve that works with the following ventilation boxes
- DucoBox Silent Standard
- DucoBox Silent Perilex
- DucoBox Silent Connect
- DucoBox Focus (⚠ Warning: Original Duco Valves are not supported! ⚠)

In the future an external housing will be made for the Open AIR Valves. This can then be installed next to any ventilation box, between it and the air duct.

For more information about the Open AIR Valve see: [Open AIR Valve](https://github.com/Flamingo-tech/Open-AIR/tree/main/Open%20AIR%20Valve) 

#### Open AIR Sensors
 TODO

# Progress:


|   Part:         |Done:	                         |Version:                       |Duco Part Number|Backwards compatible|
|----------------|-------------------------------|-----------------------------|-----------------------------|-----------------------------|
|Open AIR Mini|✔️         |V1.2          | -|✔️ 
|Open AIR Pro         |❌|-|- |
|Moisture Sensor        |✔️            |V2.0        | 0000-4218 | ✔️|
|CO2 Sensor         |✔️|V2.1| 0000-4216 | ✔️
|All-In-One Sensor         |✔️|V2.1| - | ❌ 
|Programmer         |✔️|V1.0| - | ✔️ 
|Open AIR Valve         |✔️|V1.2|- |❌
|External Open AIR Valve         |❌|❌|- |❌
|Open AIR Ventilation Box         |❌|❌|- |❌

# Backwards Compatibility

If the table above has a checkmark in the `Backwards compatible` column, then you can use the device in the original Duco Silent ventilaton box.


# Special thanks:
[@thomasvnl](https://github.com/thomasvnl) For writing the Valve firmware and valuable feedback.\
[@Septillion](https://github.com/septillion-git) Thanks for providing valuable feedback.\
[@KristofRobberechts ](https://github.com/KristofRobberechts) For providing a beautiful valve design!

