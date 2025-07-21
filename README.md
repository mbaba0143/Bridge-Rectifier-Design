# Bridge-Rectifier-Design
A Bridge Rectifier is an electronic circuit used to convert Alternating Current (AC) into Direct Current (DC). It uses four diodes arranged in a bridge configuration to allow current to flow during both halves (positive and negative) of the AC cycle, resulting in full-wave rectification.
 Title
Design and Working of a Full-Wave Bridge Rectifier
🎯 Objective / Aim
To design and demonstrate a full-wave Bridge Rectifier circuit using four diodes to convert AC (Alternating Current) into DC (Direct Current).
📂 Abstract
A bridge rectifier is one of the most important circuits used in power electronics. It is used to convert the AC voltage from a transformer or mains into a DC voltage suitable for electronic devices. In this project, we use four diodes arranged in a bridge configuration to rectify both halves of the AC input signal. This project explains the circuit, its components, working, and output waveform.


 Components Required
S.No      	Component                                  	Quantity
1          	Diodes (1N4007)                                 	4
2         	Step-down Transformer (230V to 12V)              	1
3	          Capacitor (1000µF, 25V)                         	1
4         	Resistor (1kΩ as load)                          	1
5         	Breadboard                                      	1
6          	Connecting wires                                 10

Circuit Diagram

The four diodes are connected in bridge format.
AC input is connected to the bridge.
The output is taken across a load resistor.
Capacitor used to smooth the output waveform.

Working of Bridge Rectifier
The bridge rectifier consists of four diodes (D1, D2, D3, D4) connected in such a way that they allow current to pass during both the positive and negative cycles of the AC signal.

positive Half-Cycle:
Diodes D1 and D2 conduct.
Current flows through the load in one direction.

Negative Half-Cycle:
Diodes D3 and D4 conduct.
Current again flows through the load in the same direction.

Thus, both halves of the AC input are used, producing a full-wave rectified output.
A filter capacitor is connected across the output to reduce ripples and provide smooth DC voltage.

Waveform
Input: Pure sine wave (AC)
Output (without filter): Pulsating DC
Output (with capacitor): Smooth DC with minor ripple

Applications
Power supply units for electronic devices
Battery charging circuits
DC motor drivers
Mobile charger circuits
LED drivers and adapters

Advantages
Utilizes both halves of AC input
Higher average output voltage than half-wave rectifiers
Efficient and reliable
Simple design and low cost

 Limitations
Output is not pure DC (without capacitor)
Diodes have voltage drop, reducing efficiency slightly
Capacitor needed for smoothing

 Conclusion
The Bridge Rectifier is an efficient method to convert AC to DC. It is widely used in power supply circuits. In this project, we successfully designed and demonstrated the working of a full-wave bridge rectifier using basic components. With the help of a filter capacitor, the output was made smooth enough for DC applications.




