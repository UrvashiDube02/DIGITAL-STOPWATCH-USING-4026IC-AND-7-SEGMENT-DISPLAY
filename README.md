# DIGITAL-STOPWATCH-USING-4026IC-AND-7-SEGMENT-DISPLAY

**OBJECTIVE**

The aim of the project is to design and implement a digital stopwatch using 4026 ic and 7 segment display. 

**MATERIALS REQUIRED**

1. Breadboard 
2. battery 
3. Capacitors (100nF, 10nF) 
4 .resistors 
5. switches (on,off,reset) 
6. 555 timer 
7. 4026 IC 
8. 7 segment display 
9. Connecting wires


**THEORY AND WORKING**

In this stop watch circuit we have generated one second delay by using 555 timer based astable multivibrator. By using some calculation we can easily generate one 
second delay. In astable multivibrator there is two resisters and one capacitor is responsible for delay by charging or discharging capacitor through resistors. 
Calculation formula for generating delay for astable multivibrator is given below. 

F=1/T= 1.44/(R1 + 2R2) C1 

In this project we have used R1 is 1K, R2 is 1K and C1 is 100nF. Here, the timer generates 50 ms delay, this delay is oscillations or pulse of 0 and 1. So we will use this pulse 
for triggering the seven segment decoder then seven segment decoder changes the digit number.

**CIRCUIT DIAGRAM**

![image](https://user-images.githubusercontent.com/87383888/125501612-02dc0789-9395-436a-acd5-68f45d66c057.png)

 **OUTPUT**
 
 ![image](https://user-images.githubusercontent.com/87383888/125501716-c86e760d-057a-4782-aec4-400586e6ce5d.png)


