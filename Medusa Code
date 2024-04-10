#include <Servo.h>

Servo mysevo;  //servo variable
const int buttonPin = 2;

void setup() {
  myservo.attach(9); // Servo goes on pin 9
  pinMode(buttonPin, INPUT);
}

void loop(){
  if(digitalRead(buttonPin) == HIGH){
    myservo.write(180); //What angle are we turning it? 0-180
  }else{
    myservo.write(0);
  }
}
