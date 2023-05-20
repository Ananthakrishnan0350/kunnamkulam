# BATTERY LEVEL MONITIOR
---
### IMAGE

#### ![IMAGE](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/BATTERY.png)
---
### [STIMULATION](https://www.tinkercad.com/things/1qQFvXepjBf-battery-level-monitor/editel)
---
### CODE
```

#include <LiquidCrystal.h>
float temp=0.0;
float procent=0.0;
int potency;
int leds[3] = {8,9,10};


// initialize the library with the numbers of the interface pins
LiquidCrystal lcd(12, 11, 5, 4, 3, 2);

void setup()
{
   Serial.begin(9600);     //  opens serial port, sets data rate to 9600 bps
   lcd.begin(16, 2);       // set up the LCD's number of columns and rows: 
   lcd.print("Battery is: ");
  
    for(int i = 0; i < 3; i++)
  	{
    	pinMode(leds[i], OUTPUT);
  	}
}

void loop()
{
   
//Conversion formula

   int analog_value = analogRead(A2);
    temp = (analog_value * 5.0) / 1023.0; 

  	procent = temp*20;
  
  	potency = map(analogRead(A0), 0, 1023, 0, 270);
  
  	if(potency > 10)
    	digitalWrite(leds[0], HIGH);
  	else
    	digitalWrite(leds[0], LOW);
  
  	if(potency > 100)
    	digitalWrite(leds[1], HIGH);
  	else
    	digitalWrite(leds[1], LOW);
  
  	if(potency > 150)
    	digitalWrite(leds[2], HIGH);
  	else
    	digitalWrite(leds[2], LOW);
  	
    Serial.print("v= ");
    Serial.println(temp);
    lcd.setCursor(2, 1);
    //lcd.print("V = ");
    lcd.print(procent);
  	lcd.print("%");
    delay(300);
}
```
--
# KEY CHAIN
## IMAGE
![IMAGE]
