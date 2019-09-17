# Custom program for WEIMA TH Standard Series (TH714). B

### Attention!!!

This is not an official program.
For the program to function, all devices must be connected according to the inputs and outputs installed in the program.<br>
You must understand what you are doing.<br>
You must have knowledge of electrical engineering and technological processes.<br>
The program was written to restore the dead briquette press.

-------------------------------------------------------------------

### Features of the work.

Automatic start, no preliminary preparation required.<br>
When the press is clogged, self-cleaning occurs, after self-cleaning, work continues.<br>
No encoder is required at the press outlet.

https://www.youtube.com/watch?v=vYgpMgc0Lm4

Program for another Weima briquette press - https://github.com/nvjob/custom-program-weima-th-series-a

![GitHub Logo](https://github.com/nvjob/custom-program-weima-th-series-a/blob/master/Images/Briquette%20Press%20(3).jpg)

-------------------------------------------------------------------

#### INPUTS:

I0.0 - Power.
I0.1 - Start the program in automatic mode. <br>
I0.2 - Stop the program in automatic mode. <br>
I0.3 - Manual mode. <br>
I0.4 - Vertical piston, sensor, lower position. <br>
I0.5 - Vertical piston, sensor, upper position. <br>
I0.6 - Horizontal piston, sensor, position retracted. <br>
I0.7 - Horizontal piston, sensor, position extended. <br>
I1.0 - Not involved. <br> <br>
I1.1 - Valve button. <br>
I1.2 - Accident, stop. <br>
I1.3 - Change in operating time of the screw. Min time. <br>
I1.4 - Change in the operating time of the screw. Max. time.  <br>
I1.5 - Not involved.


#### OUTPUTS:

Q0.0 - The engine of the hydraulic power station (star-delta). <br>
Q0.1 - Hydroelectric power station engine (star-delta). <br>
Q0.2 - Fan. <br>
Q0.3 - Auger. <br>
Q0.4 - Vertical piston, valve, up position (pushes down). <br>
Q0.5 - Vertical piston, valve, lower position (pushes up). <br>
Q0.6 - Horizontal piston, valve, retracts the piston. <br>
Q0.7 - Horizontal piston, valve, extends the piston. <br>
Q1.0 - Collet Piston. <br>
Q1.1 - Light Bulb Start

#### See comments in the program for more details.
