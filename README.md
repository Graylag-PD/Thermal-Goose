# Thermal Goose
## About
Thermal Goose is a collection of mechanical parts and control macro, that serve to control the chamber teperature of your 3D printer - purely by means of fans, so without risks of dedicated chamber heaters.  
The project is in **Early Alpha**, which means the basic components have been tested, but the final integration has not been done and significant parts are still missing. Expect anything and use at your own risk.  
The Thermal Goose has been designed for Voron Trident, as that is the only printer I have acess to. It should be adaptable for a V2.4 or other printers, but no effort has been done in that direction.  

##Components
The Thermal Goose has three main parts and addittional addons.
### Bed Fan
Bed fans are in place to passively heat up your chamber. Design is minimalistic and is essentially just 6020 axial fans on simple mounting poins. You will need one or two 6020 fans, heatset inserts (go into fan frame), some screws and hammerhead nuts.  
I you plan to adapt the project for V2.4, you should probably use radial fans instead. See internet, there are plenty to use.  

### Intake fan
A 12032 Radial fan has been used and is intended to be mounted into your rear panel, by the chamber bottom. The intake has input dust filter to prevent any dust accumulation.  
To assemble you will need a 12032 fan, heatset inserts, screws and a foam for a dust filter. 
![](/Assets/IMG20260521205851.jpg) ![](/Assets/IMG20260521205917.jpg)

### Control macro
TBD

### Addons
#### Chamber pressure monitor.
If you start taking chamber management and filtering seriously, you will have to care about the differential pressure inside your chamber. This addon is exactly about that and uses a differential MEMS pressure sensor for monitoring of a relative chamber pressure.  
TBD

## Contacts
If you decide to give it a chance, you should probably join our [Discord server](https://discord.gg/8a29q9gJb9)
