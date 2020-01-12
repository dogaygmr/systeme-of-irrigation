#define motor_pin 9
#define nem_sensoru A0
#define calisma_siniri 0
int nem_degeri = 0;
void setup() {
pinMode(motor_pin , OUTPUT);
Serial.begin(9600); }
void loop() {
nem_degeri = analogRead(nem_sensoru);
Serial.println(nem_degeri);
 if (nem_degeri > calisma_siniri)
{
 digitalWrite(motor_pin, HIGH); 
 delay(3000);
 digitalWrite(motor_pin, LOW);
 delay(5000);

 }

 else

 {

 digitalWrite(motor_pin, LOW);
 }

}
