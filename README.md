 Title : Autosar-Architecture-for-Engine-Speed

 Problem Statement : In modern vehicles, engine speed (RPM) must be measured accurately and shared between different vehicle systems. Traditional designs are hard to modify and do not clearly show how software components communicate. There is a need for a structured system that can measure engine speed and demonstrate proper communication between vehicle software modules.

Methodology:
*A speed sensor is used to detect the engine’s rotational speed.
*The sensor signal is sent to an AUTOSAR-based calculation module.
*The calculation module converts the sensor data into RPM values.
*The RPM value is sent to a display module using AUTOSAR interfaces.
*All software components are designed and configured using Artop.
*The complete system is simulated in MATLAB Simulink to observe real-time RPM changes.

Conclusion : The project was successfully implemented using Artop for AUTOSAR configuration and MATLAB Simulink for simulation. It clearly demonstrates how engine speed data is processed and shared between software components in an AUTOSAR-based system. This project helps in understanding real automotive ECU architecture and software communication
