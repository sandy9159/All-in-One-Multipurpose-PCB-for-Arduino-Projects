# All-in-One-Multipurpose-PCB-for-Arduino-Projects
This is multipurpose PCB specially design for arduino projects so that we can connect multiple components at once with arduino
Those who ever worked with arduino they know the pain of connecting multiple components to the arduino for there projects. so here is the answer for you all.

Not only 2 or 3 you can connect 11 components at same time & on board 5V & 9V regulator,

cross polarity protection, power indication LED,

motor power selection provision (5V or 9V or 12V) manual provision for stepper motor microstepping setting.

Wide range of input supply (9V to 24V). This is my multipurpose PCB works with Arduino Nano, I have designed it in a way that you can run 2 Stepper motors, 2 DC motors, 2 Servo motors at same time and this is not it you can even connect BT module, rotary encoder, I2C device, potentiometer at same time.

This PCB is very much helpful in building any project and no need to worry about messy wire connections.

I design this PCB in Easyeda and order it from [JLCPCB.COM](url) they offer very affordable rate for quality PCB.

**Step 1: Overview of PCB**


He we first see the overview of PCB means what is this PCB capable of and which components you can connect to the PCB.

**List of the Components you can connect to the PCB**

2 DC motor ( 9V to 24V DC)


2 Potentiometer


2 Servo motors ( 5V to 9V DC)


1 Serial device (BT module, HMI, Communication module, RX, TX)


1 Encoder (2 interrupt pin & 1 PB pin)


1 I2C device (SCL/SDA Device, display, MPU6050 etc)


2 Stepper motors


**Special features of PCB**

Wide range of power input 9V to 24V DC


Cross polarity protection


DC motor voltage selection 9V or 12 V DC


Servo motor voltage selection 5V or 9V DC


Manual microstepping setting for stepper motor


Power indication LED


L298N IC for heavier DC motor


ON board 5V and 9V regulator no need to arrange different power sources


Header pins and screw terminals for easy connections


**Step 2: PCB Design and PIN Details**


I have design circuit and PCB ineasy EDA and ordered PCB from [JLCPCB.COM](url)




[JLCPCB.COM](url) are the world leader in PCB manufacturing there PCB production rates are very much affordable and they have world class PCB production unit results fast PCB production.

I have provided the link of circuit desgin so that you can modify it as per your need if you need to change any thing.

https://oshwlab.com/sharmaz747/multipurpose-pcb

**Pin details of PCB**

**DC MOTORS**

EN1, EN2 = D9


IN1 = D7


IN2 = D8


IN3 = D10


IN4 = D11


**POTENTIOMETER**



P1 = A6


P2 = A7


**SERVO MOTORS**



S1 = D5


S2 = D6


**SERIAL COM.**



DO = TX


D1 = RX


**ENCODER**



PB = D4


IN1 = D2


IN2 = D3


**I2C PORT**



SCL = A5


SDA = A4


**STEPPER MOTORS**



EN = D12


DIR1 = A0


STP1 = A1


DIR2 = A2


STP = A3


**Step 3: Component Used**


5V DC Jack ----- 1 no


LM7805 ---- 2 nos


LM7809------1 no


4.7uF cap ------ 1 no


1uF cap ----- 2 no


47uF cap ---- 1 no


N5408 Diode ----- 1 no


FR207 Diode ------ 8 nos


5mm LED ------ 1 no


L298N IC ------- 1 no


Arduino Nano ----- 1 no


A4988 driver ------- 2 nos


Screw terminals ------ 2 x 6 nos


Male female header pins


200 ohm Resistor --- 1 no


1.5K ohm Resistor ---- 2 nos


Step 4: Arduinio Code for Demo RUN


Below is the link to download the demo code so that you can connect all the components with PCB and run them one by one with the help of encoder and 16x2 LCD display



https://drive.google.com/file/d/1ILjvVcAtpka4v8WJR...


https://youtu.be/0zuP-W4X2XU
