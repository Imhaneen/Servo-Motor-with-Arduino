#include <Servo.h>

// Define servo objects for each servo motor
Servo servo1;
Servo servo2;
Servo servo3;
Servo servo4;
Servo servo5;
Servo servo6;

// Define analog input pins for potentiometers
const int potPin1 = A0;  // Potentiometer 1 connected to analog pin A0
const int potPin2 = A1;  // Potentiometer 2 connected to analog pin A1
const int potPin3 = A2;  // Potentiometer 3 connected to analog pin A2
const int potPin4 = A3;  // Potentiometer 4 connected to analog pin A3
const int potPin5 = A4;  // Potentiometer 5 connected to analog pin A4
const int potPin6 = A5;  // Potentiometer 6 connected to analog pin A5

void setup() {
  // Attach each servo to its respective pin
  servo1.attach(2);  // Pin 2 for servo 1
  servo2.attach(3);  // Pin 3 for servo 2
  servo3.attach(4);  // Pin 4 for servo 3
  servo4.attach(5);  // Pin 5 for servo 4
  servo5.attach(6);  // Pin 6 for servo 5
  servo6.attach(7);  // Pin 7 for servo 6
}

void loop() {
  // Read potentiometer values and map to servo positions
  int pos1 = map(analogRead(potPin1), 0, 1023, 0, 180);  // Map potentiometer 1 range to servo 1 position
  int pos2 = map(analogRead(potPin2), 0, 1023, 0, 180);  // Map potentiometer 2 range to servo 2 position
  int pos3 = map(analogRead(potPin3), 0, 1023, 0, 180);  // Map potentiometer 3 range to servo 3 position
  int pos4 = map(analogRead(potPin4), 0, 1023, 0, 180);  // Map potentiometer 4 range to servo 4 position
  int pos5 = map(analogRead(potPin5), 0, 1023, 0, 180);  // Map potentiometer 5 range to servo 5 position
  int pos6 = map(analogRead(potPin6), 0, 1023, 0, 180);  // Map potentiometer 6 range to servo 6 position
  
  // Control servo motors
  servo1.write(pos1);  // Set servo 1 position
  servo2.write(pos2);  // Set servo 2 position
  servo3.write(pos3);  // Set servo 3 position
  servo4.write(pos4);  // Set servo 4 position
  servo5.write(pos5);  // Set servo 5 position
  servo6.write(pos6);  // Set servo 6 position
  
  // Delay between updates (adjust as needed)
  delay(20);  // Short delay to allow servos to reach their positions
}
