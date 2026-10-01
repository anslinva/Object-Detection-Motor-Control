# Object-Detection-Motor-Control
An Arduino-based touchless motor control system using an HC-SR04 ultrasonic sensor to detect hand movement. When a hand is detected within a set distance, the RS-775 DC motor automatically stops through an L298N motor driver, and resumes running when the hand is removed.

**Working Principle**
Hand detected within 15 cm → Motor stops
Hand moved away beyond 15 cm → Motor starts again
The distance threshold can be easily modified in the Arduino code.

**System Architecture**
        Hand / Object
             ↓
      HC-SR04 Sensor
             ↓
        Arduino Uno
             ↓
       Control Signal
             ↓
        L298N Driver
             ↓
        RS-775 Motor

**Applications**
The basic concept can be extended to:
-Touchless control systems
-Contactless switches
-Safety-based motor stopping
-Human-machine interaction
-Smart automation systems
