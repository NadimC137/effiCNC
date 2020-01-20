# effiCNC
This CNC was made fully out of 18mm plywood and other cheap components (most of them are available in aliexpress and local hardware stores). This repo is basically a do-it-yourself guide for those who want to make one for themselves.

## About The Machine
Work area of this machine is 27cm x 22cm. This was made mostly out of 18mm thick plywood. Other mechanical parts were mostly bought from aliexpress or homemade.A DC uninterrupted power supply was designed using DIY circuitry for emergency in any kind of power failure. This machine can cut even aluminium with the right feed rate and spindle rpm.

 
 
 ## Video 
 ### Cutting Plywood
<a href="https://youtu.be/KvGP34OzlSg" target="_blank"><img src="https://img.youtube.com/vi/KvGP34OzlSg/0.jpg" 
alt="Click to view: effiCNC: Engraving HELLO" width="500" border="1" /></a>

### Cuting Aluminium
<a href="https://youtu.be/ikTCvxNO6DQ" target="_blank"><img src="https://img.youtube.com/vi/ikTCvxNO6DQ/0.jpg" 
alt="Click to view: effiCNC: Engraving HELLO" width="500" border="1" /></a>

### PCB Fabrication

<a href="https://youtu.be/KvGP34OzlSg" target="_blank"><img src="https://img.youtube.com/vi/KvGP34OzlSg/0.jpg" 
alt="Click to view: effiCNC: Engraving HELLO" width="500" border="1" /></a>




## Design
Full structure was designed in Solidworks (files are given). Other mechanical parts used are bought from aliexpress (details and links will be given soon)

<img src="https://github.com/NadimC137/effiCNC/blob/master/images/Untitled-1.png" width="800">

## Control
For controlling the hardware I have used GRBL 0.9 with arduino UNO and CNC shield v3.0. For gcode conversion, i usually use easel from inventables, as it is free to use with a lot of features. For sending gcode to machine i use Universal Gcode Sender Platform. Links for all of these are given below.

* [GRBL](https://github.com/gnea/grbl)
* [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield/)
* [Easel](http://easel.inventables.com/)
* [UGS Platform](https://winder.github.io/ugs_website/guide/platform/)
