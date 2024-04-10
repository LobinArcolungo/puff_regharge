# Puff Battery Cell Recharger
This progect aims to recharge lithium batteries from PUFF e-cigrettes and any other kind of disposable vapes.
No code is involved in the project but just a couple of .stl files and some photos to replicate what i did.

This kind of cells are rechargeable hundreds of times despite their limited capacity so they can be used for small electronic projects and for IoT devices.
With this device I hope to help other people find a way to easily recharge them.

## Images
  <img src="Images/Device_top.JPG" width="400" height="auto">

## Components
- Old power bank to salvage the recharging chip from 
- A 3d printer of any sort
- Basic soldering skills
- Two thin wires (e.g. broken led pins halved are fine)
- Double pin socket from an arduino kit
  <br> <img src="Images/Connector.JPG" width="400" height="auto">

## Guide

### 1st step: Gathering the chip
Disassemble the powerbank exposing it's chip.
<br><img src="Images/Power_bank_disassembled.JPG" width="400" height="auto">
<br>With the soldering iron gently touch the cables leading to the battery in the connecting point to unsolder them.

### 2nd step: Design the enclosure
Design and print the enclosure for the device. If you have the same components as me you can download the .stl files from the Models folder.
Iused a Elegoo Saturn resin printer
Remember to scale the prints of about 6-7% to give the sufficient tolerance to fit everything. e.g. printing the models at 107% scaled size should be fine
<br><img src="Images/Case_open_1.JPG" width="400" height="auto"> 
    <img src="Images/Case_open_1.JPG" width="400" height="auto">

### 3rd step: Solder the circuit
The circuit is pretty simple, it's just the connector soldered to the chip with two thin wires.
<br><img src="Images/Circuit_soldered.JPG" width="400" height="auto"> 
<br><img src="Images/Circuit_bottom.JPG" width="400" height="auto"> 

### 4th step: Assembly
Position the circuit inside the 3d models

## Documentation
These are the videos that inspired me for this project. 
Disassembly: https://www.youtube.com/watch?v=ukvT_RBx-4U

Actual tutorial: https://www.youtube.com/watch?v=M88e1r8nvYk

Basic idea: 
https://www.youtube.com/shorts/beWTIUarKYY
https://www.youtube.com/watch?v=rG7qLbuWvK8&t=647s

Example of recharge in the wrong way: 
https://www.youtube.com/watch?v=MG47qHrulyI
https://www.youtube.com/watch?v=NkLQbNGd8ro&t=58s
