# Bluetooth Controller VR_Lioneye
I designed this controller package for my blueetooth controller(VR_Lioneye). I can not find any project with this controller. I convert my playstation 2 controller codes to this. I hope it helps!


Picture of my controller

![alt text](https://raw.githubusercontent.com/malisasmaz/Bluetooth_Controller_VR_Lioneye/master/images.jpg)


------------


Here is the guide to help user's who are trying to do figure out how to integrate this VR Controller Input System with Unity.<br />
Basically this controller is having 4 modes;
- @ + A or (A) : Mouse Mode
- @ + B or (D) : Not working for me
- @ + X or (B) : Horiozontal Bluetooth controller mode (this is the mode where the scripts works perfectly fine.)
- @ + Y or (C) : Vertical Bluetooth controller mode

<br />
After understanding the mode, let's move on to unity and understand Unity Input System,<br />

Hold on we still need to understand all the joystick button #numbers.<br />

In mostly VR Controller, the mapping is as below.

- joystick button 3 - Y or (C)<br />
- joystick button 0 - A or (A)<br />
- joystick button 2 - X or (B)<br />
- joystick button 1 - B or (D)<br />
- joystick button 10 - Hit (button located at side of controller)<br />
- joystick button 11 - @ button of controller.<br />
- Horizontal - you may have one already created and if not will guide you below.<br />
- Vertical - you may have one already created and if not will guide you below.<br />

*Now before starting your project you need to create all the axis buttons in **Unity Input System**.*<br />

- For Horizontal and vertical button you need to create a button with Type as "Joystick Axis" and in Axis Y for Horizontal and X for Vertical Axis.<br />

- For other button just name it properly and in Alt Positive Button replace it with appropriate mapping buttons from list above.
