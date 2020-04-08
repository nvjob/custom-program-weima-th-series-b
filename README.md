# Custom program for WEIMA TH Standard Series (TH714) (Briquette Press). B 4.1
#### [nvjob.github.io/sources/custom-program-weima-th-series-b](https://nvjob.github.io/sources/custom-program-weima-th-series-b)

![GitHub Logo](https://raw.githubusercontent.com/nvjob/nvjob.github.io/master/repo/other%20sources/weima%20th%20b/40/pic/Briquette%20Press.jpg)

### Attention!!!
This is not an official program.
For the program to function, all devices must be connected according to the inputs and outputs installed in the program.<br>
You must understand what you are doing.<br>
You must have knowledge of electrical engineering and technological processes.<br>
The program was written to restore the dead briquette press.

### Features of the work.
Automatic start, no preliminary preparation required.<br>
When the press is clogged, self-cleaning occurs, after self-cleaning, work continues.<br>
No encoder is required at the press outlet.

[youtube.com/watch?v=vYgpMgc0Lm4](https://www.youtube.com/watch?v=vYgpMgc0Lm4)

**Program for another Weima briquette press** - [github.com/nvjob/custom-program-weima-th-series-a](https://github.com/nvjob/custom-program-weima-th-series-a)

-------------------------------------------------------------------

### Prerequisites
For TH714 and compatible <br>
Siemens S7-200

### Information

![GitHub Logo](https://raw.githubusercontent.com/nvjob/nvjob.github.io/master/repo/other%20sources/weima%20th%20b/40/pic/Scheme.png)

#### INPUTS:
I0.0 - Power.
I0.1 - Start the program in automatic mode. <br>
I0.2 - Stop the program in automatic mode. <br>
I0.3 - Manual mode. <br>
I0.4 - Vertical piston, sensor, lower position. <br>
I0.5 - Vertical piston, sensor, upper position. <br>
I0.6 - Horizontal piston, sensor, position retracted. <br>
I0.7 - Horizontal piston, sensor, position extended. <br>
I1.0 - Not involved. <br>
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

-------------------------------------------------------------------

### Instruction manual

![GitHub Logo](https://raw.githubusercontent.com/nvjob/nvjob.github.io/master/repo/other%20sources/weima%20th%20b/40/pic/Scheme%202.jpg)

1. Hour meter, counts the hours worked in the process in automatic mode. <br>
2. The start of the hydroelectric station. If there are no malfunctions (the “7” lamp should be lit), the engine of the hydraulic power station starts. <br>
3. Stop the hydroelectric station. If automatic mode has been started, then it also ends. <br>
4. Start auto mode. The press starts in automatic mode, the press is initially cleaned (the light on the “4-5” switch blinks), after successful cleaning, the press goes into normal operation (the light on the “4-5” switch is on). If the engine of the hydraulic power station has not been started, the automatic mode will not start. Switch “8” should be in position “a” “Auto”. <br>
5. Stop auto mode. the press is automatically cleaned (the lamp on the “4-5” switch blinks), after successful cleaning, the automatic mode ends (the lamp on the “4-5” switch goes out). If you press the button when the press is not started in automatic mode, then one auto-cleaning cycle will occur (the light on the “4-5” switch blinks). <br>
6. Switching the time of feeding the material into the chamber with a screw. The shorter the time, the smaller the portion and the briquette itself at the exit. Positions: a - 1.5 seconds, b - 2 seconds, c - 2.5 seconds. <br>
7. Work status indicator. If there are no malfunctions (emergency sensors are connected and not triggered, all the machines are on, the emergency stop button is not pressed), then the lamp should light up green. <br>
8. Switching between automatic and manual mode. Position “a” - automatic mode, position “b” - manual mode. Manual mode blocks the operation of the press in automatic mode and allows you to manually control the valves of the hydraulic station. If you put the press into manual mode during operation in automatic mode, then the automatic mode ends without auto-cleaning. <br>
9. Manual control of the valves of the hydraulic station of the vertical piston. Position “a” - the piston drops, position “b” - the piston rises. Switch “8” should be in position “b” “Manual”. <br>
10. Managing the valves of a horizontal piston hydraulic station in manual mode. Position “a” - the piston retracts, position “b” - the piston extends. Switch “8” should be in position “b” “Manual”. <br>
11. Control valves of the hydraulic collet. Position “a” - collet is closed, position “b” - collet is open. Switch “8” should be in position “b” “Manual”.

In automatic mode, protection against stopping the press when clogging material in a vertical and horizontal piston is provided. When clogging, the press is automatically cleaned; after auto-cleaning, the press switches to the normal mode of operation in automatic mode. Auto-cleaning will be performed until the press is cleaned for normal operation. During self-cleaning, the light on the “4-5” switch flashes.

-------------------------------------------------------------------

**Patrons:** [nvjob.github.io/patrons](https://nvjob.github.io/patrons)<br>
*You can become one of the patrons, or make a sponsorship donation.*

-------------------------------------------------------------------

**Authors:** [#NVJOB. Developer Nicholas Veselov. Разработчик Николай Веселов. Санкт-Петербург.](https://nvjob.github.io)

**License:** GNU GPL v3.0. Clarification of licenses - [nvjob.github.io/gnu-license](https://nvjob.github.io/gnu-license)

**Support:** [Report a Problem](https://nvjob.github.io/reportaproblem/).
