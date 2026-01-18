# FINAL-PROJECT-Student-Portfolio-for-COSC-111
# FIDELSON JOHN PAUL M.
# BSCS 4-B
**Lab Activity 1: Digital Output (Blinking)

**An activity that defines an array of 5 LEDs and turns them all High (On) and then Low (Off) in a simple sequence. 
It demonstrates how to control multiple digital outputs simultaneously.


**Lab Activity 2: Analog Output (Fading)

**This script introduces PWM (Pulse Width Modulation). Instead of just turning LEDs on or off, 
it uses nested loops and analogWrite to gradually increase and decrease the brightness (0 to 255) of 5 LEDs, creating a fading or "breathing" effect.

**Lab Activity 3: Analog Input (Sensors) **

This activity introduces sensors. It reads data from a Thermistor (temperature) and a Photoresistor (light). 
It uses logic to determine if a "Fire" is present (High Temp + High Light) and triggers an alert (LED/Buzzer) if specific thresholds are met.

**Lab Activity 4: Serial Input & String Processing **

This activity focuses on Serial Communication. It monitors temperature like the previous lab,
but it adds a feature where the user can type commands (specifically the word "stop") into the Serial Monitor to manually disable the blinking LED alert.


**Lab Activity 5: PC-to-Arduino Control (Python Integration) **

This lab shifts control to the computer. The Arduino acts as a receiver, waiting for single-letter commands ('R', 'G', 'B', 'A') to toggle specific LEDs.
While the Python Script provides a menu on your computer screen for you to select which LED to turn on, demonstrating how external software can control hardware.

**Lab Activity 6: Two-Way Communication (Buttons & Events)**

This is an activity about demonstrating bidirectional communication.
The Arduino reads physical buttons and sends a signal to the PC when one is pressed
and the python script listens for these signals and updates the display or sends commands back to toggle LEDs. It uses a header file (.h) to keep the main code


**Lab Activity 7: Web-Based IoT Control (FastAPI + Arduino)**
The activity introduces Web API integration with hardware. Unlike previous labs that used standard Python scripts, this lab uses FastAPI to create a web server that allows you to control the Arduino through HTTP requests (web URLs).
