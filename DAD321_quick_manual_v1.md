# DAD-321 Quick Guide

## 1. Preparation
1) Air,2 water lines (Industrial for cooling & DI for cutting) ON
2) Blade install(see section4)
3) Turn switch ON
4) Press SYS INIT(if instruction indicates)
5) Press F4 -pick device or set up new device(see section5)
6) Press F10 -device set
6) Press F5 ->F1  -pick blade
6) Press EXIT -Main Menu
7) Move microscope out of the chuck
8) Mount the tape and the wafer, VAC ON

## 2. Hairline Alignment
1. Put a dummy wafer for hairline alignment
1. Press F5 twice -Hairline alignment
2. Enter the detail of the device data requested
3. Press ENTER & START - Cut for once
4. Press Y keys and HAIR keys to make sure 3 hair lines in the kerf.
5. Press ENTER to excute hairline correction
6. EXIT -> Main menu
7. Remove the dummy wafer



## 3. Semi-Auto cut
1. Put a real wafer
1. Press F2 -Semiauto cut
2. Spindle ON
3. Cut water ON
### 3.1 Alignment
1. Press F4 - theta alignment<br>
&nbsp; -Press Y keys and theta keys(make it SLOW and repeatedly not holding it down) <br>
&nbsp; &nbsp; -to align the street on the wafer to the center of the hairline <br>
&nbsp; -Press F5 -Automatically move the wafer to the left. And do the same alignment there. <br>
4. Repeat the operation above till completely aligned at both 2 points. 
6. (Optional) Press Y keys and HAIR NARROW or WIDE, to adjust the center of the hairline to the center of the street. 
7. Press ENTER.
### 3.2 Cut
5. Press X/Y to the line to cut
6.Press F5(from front to back) or F10(from back to front) <br>
Note: It rotates 90 degrees(Counterclockwise), when it starts cutting.
5. Press START
6. Press STOP (it finishes the last cut before cutting pauses)
### 3.3 Stop correction
1. Press Y keys and HAIR keys to make sure 3 hair lines in the last kerf.
1. Press F1 -Hairline adjustment. This confirms the adjustment done in 1.
2. Press F5 -Cut position adjustment. ->F5 again<br>  
### 3.4 Finish
7. EXIT*2 and turn off SPINDLE and CUT WATER 
8. Main menu

## 4.Blade replacement
1) Press F5, Blade maintenance
2) Press F1, Blade Exchange
3) Open the splash cover 
4) Remove the wheel cover(black part smaller one out of 2)
5) Remove flange nut(larger one) with 400cN.m, rotating clockwise
6) Remove flangeB and Blade
7) Set new blade, and update or create new blade data <br>
&nbsp; -Blade Spec: Blade Name<br>
&nbsp;- Blade type: Flange/Hub (select)<br>
&nbsp;- Hubbless type Flange O.D: 49.5mm<br>
8) Idle running for 10 min<br>
&nbsp;- Spindle: ON<br>
&nbsp;- Cut water: ON<br>
9. Set up<br>
&nbsp; -Press SET UP<br>
&nbsp; -Press ENTER for 4 times till set up done and back to Blade maintenance<br>
10) Press EXIT and back to Main menu

## 5. Device data setting
1) Press F4 -device data list
2) Press F2 -copy an old one to start with
3) Press ENTER - input data<br>
&nbsp; -CUT MODE: A(90 degrees)<br>
&nbsp; -CUT Shape: RND/Square<br>
&nbsp; -Work size: RND= Diameter<br>
&nbsp; Y index: Cut pitch<br>
&nbsp; -Tape Thickness: 0.070mm<br>
&nbsp; -Blade Height: 0.065mm(cut through the wafer)<br>
&nbsp; -Feed Speed: 0.30mm/s<br>
4) ->ENTER, ->EXIT*2times
4) Main menu

## 6. Shutdown
1. Main menu
2. Press SYS INIT
3. Clean the below both right and left of the chuck with N2
4. Turn the switch OFF

## 7. Error Handling
1) Initialize system<br>
&nbsp; Press SYS INIT<br>
2) Sensor calibration<br>
&nbsp;F3- Setup functions <br>
&nbsp;F4- Sensor caliblation setup<br>
3) Booting Issue (2/18/2025) <br>
&nbsp;Situation: Powers up but dosen't boot after power outage on last weekend <br>
&nbsp;Solution: Call Giorgio Tech and send cpu, emsuram, both motor control pcbs<br>
## 8. Reference 
[UIC DAD321 Manual](https://github.com/RyutaroMatsumoto/DAD321_Quick_Guide/blob/main/DAD321/Disco-Model-DAD321-Dicing-Saw.pdf)

