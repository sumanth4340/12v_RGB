#define red 9
#define green 10
#define blue 11
int brightness;
int fadeAmount = 5;

void setup()
{

}

void loop()
{

  analogWrite(red, brightness); 
  analogWrite(green, brightness); 

  brightness += fadeamount;

  if (brightness < 0 || brightness > 255 )
  {
    fadeAmount = -fadeAmount; 
  }
  delay(30); 
}
