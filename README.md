# Automatic-Bacteria-Streaking-Robot
This is a simple showcase of my thesis project where you can find some photos and videos about the building process and tests with real bacteria.

<h1>First conceptions</h1>

 ### [YouTube Demonstration](https://www.youtube.com/shorts/pXCyQN5C-c0)

<h2>Description</h2>
Project consists of a cartesian robot whose main goal is to draw the specific patterns utilized to streak bacteria samples in solid agar media culture, so it dispenses a small amount of bacteria sample with a micropippete and then uses the bacteriological loop to streak the whole plate with a certain pattern, right now, the device is capable of drawing four different kinds of patterns. It uses stepper motors nema 17 fot the motion, Arduino Mega as microcontroller with the firmware GRBL.
<br />


<h2>Languages and Utilities Used</h2>

- <b>C++</b> 
- <b>ESP32</b>
- <b>SolidWorks</b>
- <b>Fusion360</b>
- <b>3D printing</b>
- <b>GRBL</b>
- <b>Arduino Mega</b>




<h2>Device building process:</h2>

<p align="center">
CAD design: <br/>
<img src="https://raw.githubusercontent.com/Brengas/Automatic-Bacteria-Streaking-Robot/main/images/Bacteria_vistageneral.jpg" height="70%" width="70%" alt="CAD design SolidWorks"/>
<br />
<br />
Working prototype:  <br/>
<img src="https://raw.githubusercontent.com/Brengas/Automatic-Bacteria-Streaking-Robot/main/images/Bacteria_proto3vistas.jpg" height="70%" width="70%" alt="Prototype views"/>
<br />
<br />
Dispense Process: <br/>
<img src="https://raw.githubusercontent.com/Brengas/Automatic-Bacteria-Streaking-Robot/main/images/Deposito_prototipo3.jpg" height="50%" width="50%" alt="Sample dispense"/>
<br />
<br />
Streaking:  <br/>
<img src="https://raw.githubusercontent.com/Brengas/Automatic-Bacteria-Streaking-Robot/main/images/Estriado_Prototipo3.jpg" height="50%" width="50%" alt="Spiral Streaking"/>
<br />
<br />
Firsts cultures of E. Coli made by the robot:  <br/>
<img src="https://raw.githubusercontent.com/Brengas/Automatic-Bacteria-Streaking-Robot/main/images/bacteria_conteo.jpg" height="70%" width="70%" alt="E. Coli Culture"/>
<br />
<br />

## How It Works
1. The user inputs the streaking pattern via the touchscreen interface.
2. The Arduino Mega, running GRBL, controls the NEMA 17 motors to move the streaking tool.
3. The ESP32 handles the touchscreen interface and communicates with the Arduino.
4. The robot performs the streaking process autonomously, with minimal human intervention.

## Results
- Achieved near-complete automation of the streaking process.
- Reduced human involvement by 70%, minimizing contamination risks.
- Demonstrated the potential for use in medical and laboratory settings.

## Future Improvements
- Integration with laboratory information systems for automated sample tracking.
- Enhanced user interface with additional features like pattern customization.
- Optimization of motor control for faster and more precise movements.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
