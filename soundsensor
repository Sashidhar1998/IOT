int soundSensor = 2;
int LED =3;
void setup()
{
pinMode(soundSensor , INPUT);
pinMode(LED,OUTPUT);
}
void loop()
{
int status = digitalRead(soundSensor);
if(status == 1)
{
digitalWrite(LED , HIGH);
}
else
{
digitalWrite(LED , LOW);
}
}
