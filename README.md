# Arduino-projects---sriram
basic arduino programming projects
# Arduino LED Blinking System

## Objective
To understand basic Arduino programming and control an LED using digital output.

## Components Used
1. Arduino Uno  
2. LED  
3. Resistor  

## Working Principle
The Arduino sends HIGH and LOW signals to the LED through pin 13, making it turn ON and OFF at regular intervals.

## Circuit Diagram / Output
![LED Blink](blinking led.png)

## Code

void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
