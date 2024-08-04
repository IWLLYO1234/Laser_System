# Laser_System
This Arduino program is designed for a laser detection system that monitors whether a laser beam is interrupted. The setup includes a Light Dependent Resistor (LDR) to detect the presence of the laser beam, a buzzer to alert when the beam is broken, and a button to reset the system.

Key Features:
Laser Detection: The LDR constantly reads the intensity of light from the laser. If the light level drops below a defined threshold, indicating that the laser beam has been obstructed, the system triggers an alarm.

Buzzer Alert: Upon detecting an interruption in the laser beam, the program activates a buzzer, which emits a periodic beeping sound to alert users of the breach.

Manual Reset: The system includes a reset button that can be pressed to stop the buzzer and reset the detection flag, allowing the system to resume monitoring.

Usage:
Intrusion Detection: The system can be used in security applications to detect intrusions or unauthorized access when a laser beam across a protected area is broken.

Object Counting: It can also be used in setups where counting objects passing through a laser beam is required.
This program effectively combines the components to create a responsive and reliable laser detection system suitable for various applications, offering a clear alert system and a simple reset mechanism.
