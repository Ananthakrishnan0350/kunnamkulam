# 10 Days internship 
----
## DAY 1
In day one we have learned how to make an account in github,github is a website that we can store work so any one can see our work that makes easy to for the interviews to how our experiance in our work,then we have made our own resporty in the website and it was fun learning and making my own documentry.

 ## DAY 2
 ### TINKERCAD
In day 2 we have leraned about tinkercad,it is a website that we can make our own circuit design's,with the help of our trainer jinesh sir i have made my own small circuit,it is a green colour led that i made in bread board every one can see the image down as i linked the image as day 2....
It is a sunny climate in jothys campus and lot of students in campus it is relif that we are not alone in this campus because there is project expo on is conduting here in all kerala level it is such pleasure watch new inovation by some smart students from not only jothy but also other collage students 
### [day 2](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/led1.png)
----
## DAY 3
[Stimulation](https://www.tinkercad.com/things/hgkn6KzBFZs-four/editel)
[day 3](https://www.tinkercad.com/things/1SX4MZ2Kp0F-terrific-hillar-blorr/editel)
### AND Gate 
#### Circuit Diagram
![circuit](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/day%203.png)
#### Schematic Diagram
![schematic](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/day%203.1.png)
#### Components Used
![components](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/day%203.2.png)
### [AND gate stimulation](https://www.tinkercad.com/things/5ZM2FvjwY36-and-gate/editel)
----
#### LED Blinking using adruno
![ led blink](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/blink.png)
```// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);https://www.tinkercad.com/things/hgkn6KzBFZs-four/editel
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}https://www.tinkercad.com/things/0umwuGT12uz-analog/editel
```
### [Stimulation](https://www.tinkercad.com/things/hgkn6KzBFZs-blink/editel)
---
#### 2 LED Blinking 
![Two LED Blink](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/two%20led.png)
```// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
### [Stimulation](https://www.tinkercad.com/things/hgkn6KzBFZs-blink/editel)
---
4 LED Blinking
####  Diagram
![circuit](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/4%20led.png)
#### Program
```
// C++ code
//
void setup()
{
  pinMode(2, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(2, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(4, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(4, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(7, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
 ### [Stimulation](https://www.tinkercad.com/things/hgkn6KzBFZs-four/editel)
 ---
 ## Day 4
 ---
 ## Day 5
 ![analog potentimeter](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/arudno.png)
 #### program
 ```
const int potpin = A0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  int potvalue = analogRead(potpin);
  Serial.println(potvalue);
  delay(100);
}
```
### [stimulation](https://www.tinkercad.com/things/0umwuGT12uz-analog/editel)
#### 7 segment 
###![segment](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/SEGMENT.png)
```unsigned const int A = 13;
unsigned const int B = 12;
unsigned const int C = 11;
unsigned const int D = 10;
unsigned const int E = 9;
unsigned const int F = 8;
unsigned const int G = 7;
unsigned const int H = 6;


void setup(void)
{
  pinMode(A, OUTPUT);
  pinMode(B, OUTPUT);
  pinMode(C, OUTPUT);
  pinMode(D, OUTPUT);
  pinMode(E, OUTPUT);
  pinMode(F, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(H, OUTPUT);
}

//My Functions

void zero(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void one(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, LOW);
  digitalWrite(C, LOW);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void two(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, LOW);
  digitalWrite(H, LOW);
}

void three(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void four(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, LOW);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void five(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void six(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void seven(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void eight(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void nine(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

// Start
void loop(void)
{
  zero();
  delay(1000);
  
  one();
  delay(1000);
  
  two();
  delay(1000);
  
  three();
  delay(1000);
  
  four();
  delay(1000);
  
  five();
  delay(1000);
  
  six();
  delay(1000);
  
  seven();
  delay(1000);
  
  eight();
  delay(1000);
  
  nine();
  delay(1000);
}

```
[Stimulation](https://www.tinkercad.com/things/arEtaNelsyP-7-segment/editel)
## day 6
---
## DAY 7
### 0 To 9 Display Using Potentiometer
![circuit](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/IMG/Pot.png)
### Code
```
const int potPin=A0;

void setup(){
  Serial.begin(9600);
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
}
void loop()
{ 
  int potvalue = analogRead(potPin);
  Serial.println(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
} 
```
### [Stimulation](https://www.tinkercad.com/things/arEtaNelsyP-7-segment/editel)
## ASSIMENT
[Assiment](https://github.com/Ananthakrishnan0350/kunnamkulam/blob/main/Assiment.md)


