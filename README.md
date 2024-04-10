# Puff Battery Cell Recharger
## Recharge The garbage! Regharge!
This progect aims to recharge lithium batteries from PUFF e-cigrettes and any other kind of disposable vapes.
No code is involved in the project but just a couple of .stl files and some photos to replicate what i did.

This kind of cells are rechargeable hundreds of times despite their limited capacity so they can be used for small electronic projects and for IoT devices.
With this device I hope to help other people find a way to easily recharge them.

## Images
  <img src="Images/Front_image.PNG" width="400" height="auto">

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
<br><img src="Images/Case_open_2.JPG" width="400" height="auto">

### 3rd step: Solder the circuit
The circuit is pretty simple, it's just the connector soldered to the chip with two thin wires.
<br><img src="Images/Circuit_soldered.JPG" width="400" height="auto"> 
<br><img src="Images/Circuit_bottom.JPG" width="400" height="auto"> 

### 4th step: Assembly
Position the circuit inside the 3d models that should fit together. To join them you can use some tape, some glue or some resin.
Before joining them remember to try the circuit with a discharged power cell
<br><img src="Images/Use_example.JPG" width="400" height="auto"> 

### 5th step: Use the device
You can use directly the wires of a battery or if the battery doesn't have wires you can use two jumper wires.
<br><img src="Images/Device_top.JPG" width="400" height="auto">
<br>ATTENTION! use only batteries with the proper voltage (e.g. 3.7V and 500mah)


## Documentation
These are the videos that inspired me for this project. 
<br>Disassembly: 
<br>https://www.youtube.com/watch?v=ukvT_RBx-4U
<br>
<br>Actual tutorial: 
<br>https://www.youtube.com/watch?v=M88e1r8nvYk
<br>
<br>Basic idea: 
<br>https://www.youtube.com/shorts/beWTIUarKYY
<br>https://www.youtube.com/watch?v=rG7qLbuWvK8&t=647s
<br>
<br>Example of recharge in the wrong way: 
<br>https://www.youtube.com/watch?v=MG47qHrulyI
<br>https://www.youtube.com/watch?v=NkLQbNGd8ro&t=58s
