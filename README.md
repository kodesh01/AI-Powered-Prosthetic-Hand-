
🤖 Prosthetic Arm Using EXG Sensor
A project that brings intuitive control to prosthetic arms by interpreting muscle signals (EMG) with an EXG sensor and an Arduino.

✨ Overview
This project designs and implements a functional prosthetic arm prototype. It uses an EXG sensor to read Electromyography (EMG) signals from a user's residual limb muscles. These signals are processed to intuitively control the movements of a 3D-printed prosthetic hand actuated by servo motors.

🛠️ Tech Stack
Hardware: Arduino Nano, EXG Sensor (EMG), Servo Motors, 3D-Printed Prosthetic Hand
Software: Arduino IDE, Python, OpenCV (for an alternative CV-based control model)

🔧 How It Works
Signal Acquisition: Electrodes placed on the skin capture raw EMG signals from muscle contractions.
Signal Processing: The EXG sensor pill converts these analog signals into digital values.
Microcontroller: The Arduino Nano reads the processed values and maps them to specific hand movements (e.g., open, close, grip).
Actuation: Based on the command, the Arduino drives the servo motors, which manipulate the prosthetic fingers via a string-based mechanism.


🎯 Key Features
Intuitive muscle-based control.
Low-cost, 3D-printed design.
Supports basic grasping and movement patterns.

🔮 Future Work
Potential enhancements include integrating voice control for alternative command input and employing advanced machine learning models for more precise gesture recognition.

