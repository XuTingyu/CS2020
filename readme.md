#
```
https://github.com/MyFirstSecurity2020/python2020

```


CECILINO TSAI
Ine
18
19
20
25
26
20
30
Blink2 | Arduino 1.8.19
Sketchy Blinking a LED by usel
int ledPin - 10; // declare pin1® as ledpin
int numBlinks: // vartable to store the number of blinks
String LedOnMessage
Red LED is turned on"; // this is a string with information
String LedOffMessage
Red LEd is turned off"; // this is a string with information
setupO
[
pinkode (ledPin, OUTPUT;
I/ set pin10 as output pin
digitalirite(ledPin, LON); // set the pin value on low at the begin: 2-bit
Serial, begin(9600) :
Serial, printin("How Many Times Do You Want the Red LEDs to blink?"); //Prompt User for Impy
shite (Serial, availableO
0) f
1 Wait for User to Input Data
continue:
numBlinks
Serial, parseInt@; //Read the data the user has input
Serial printIn(String(
"The user has choosen the number:
numBlinks);
For (int counter » 1; counter < numBlinks; counter») [
Serial-printin(String) counter + LedOrMessage);
digitalärite(ledPin, HIGD;
delay (500) ;
Serial-printin(StringO+counter
+LedOffMessage);
digitalkrite(ledPin,LOW);
deLay (580) ;
"duino examples/LED/LedA-r

