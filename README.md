# -Arduino-LED-Button-Control-
Control three LEDs using three push buttons with an Arduino Uno.
This project demonstrates how to control three LEDs using three push buttons with an Arduino Uno. Each button controls one LED, allowing for simple digital input/output interaction. This is a great beginner project for understanding how microcontrollers handle user input and output signals.

 Components Required  
To build this project, you will need the following components:

- Arduino Uno board  
- 3 × LEDs (Red, Green, Blue)  
- 3 × 220Ω resistors  
- 3 × Push buttons  
- Breadboard  
- Jumper wires  
- USB cable for programming the Arduino  

 Circuit Connections  
Each push button and LED is connected to the Arduino as follows:

| Component | Arduino Pin | Resistor         | GND |
|-----------|--------------|------------------|-----|
| Button 1  | D5           | 10kΩ pull-down   | Yes |
| Button 2  | D6           | 10kΩ pull-down   | Yes |
| Button 3  | D7           | 10kΩ pull-down   | Yes |
| LED 1     | D2           | 220Ω             | Yes |
| LED 2     | D3           | 220Ω             | Yes |
| LED 3     | D4           | 220Ω             | Yes |

 Important: Ensure that all ground connections are properly linked to the Arduino GND pin to maintain a common ground across the circuit.

 Project Behavior  
Once powered and programmed, the three push buttons will control the three LEDs as follows:

- Pressing Button 1 turns on LED 1.  
- Pressing Button 2 turns on LED 2.  
- Pressing Button 3 turns on LED 3.  
- Releasing any button turns off its corresponding LED.  

This behavior is useful in applications like:

- Simple control panels  
- Educational demonstrations  
- Interactive LED displays  
- DIY electronics projects  

 How to Use  
1. Assemble the circuit as described above.  
2. Upload the Arduino sketch using the Arduino IDE.  
3. Power the Arduino using a USB cable or external power.  
4. Press each button to control its corresponding LED.  

 Notes  
- Ensure that the resistors are correctly placed to prevent damage to the LEDs and ensure stable button input.  
- If the LEDs do not light up, check the orientation and wiring.  
- You can expand this project by adding more buttons, sensors, or integrating it into a larger system.  

⭐ Created by Alyaa
