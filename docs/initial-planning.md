## Functionality

- 🧠Control: 2x Arduino Unos, USB cables 2x, Breadboard, Jumper Wires.
- 🤖XY gantry: 2x NEMA 17 stepper motors connected to 2x TMC2209 stepper drivers spinning GT2 belt pulley to convert motor rotation to linear motion. (See example:https://www.youtube.com/watch?v=yElA7GaP7SQ)
- 🦾Moving pieces: 3D printed carriage clamped onto X-axis belt with a weak magnet on top to attract chess pieces. Will only move between pieces to avoid attracting unwanted pieces.
- ⚡️Power: 12V power supply for external power to feed motors, Buck Converter to convert 12V to 5V safely to seperate power cleanly.
- ♟️Pieces: Modified chess pieces with small magnet inside.
- Linear Motion System: Metal linear rails with sliding block for XY gantry precision.
- Limit Switches: Buttons on edges to prevent crashing the motors into the frame.
- Frame: Either wood, acrylic or aluminum to hold board flat, keep rails aligned and minimize vibrations.

  
## Using 2 Arduino Unos

Decided to use 2 Arduino Unos:
- One for controlling the motors which control the pieces.
- One for reading sensors, LEDs and displays.
Why?:
-Arduino Uno is cheap.
-One Arduino Uno has little amount of pins making it not highly scalable.

