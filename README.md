 Title : Autosar-Architecture-for-Engine-Speed

 Problem Statement : In modern vehicles, engine speed (RPM) must be measured accurately and shared between different vehicle systems. Traditional designs are hard to modify and do not clearly show how software components communicate. There is a need for a structured system that can measure engine speed and demonstrate proper communication between vehicle software modules.

Methodology:
*A speed sensor is used to detect the engine’s rotational speed.
*The sensor signal is sent to an AUTOSAR-based calculation module.
*The calculation module converts the sensor data into RPM values.
*The RPM value is sent to a display module using AUTOSAR interfaces.
*All software components are designed and configured using Artop.
*The complete system is simulated in MATLAB Simulink to observe real-time RPM changes.

Conclusion : This project successfully measures and displays engine speed using the AUTOSAR architecture. It clearly shows how different automotive software components communicate with each other in a structured way. The simulation helps understand real-time engine behavior without hardware. This project improves understanding of AUTOSAR-based ECU design and is useful for automotive embedded system development.
