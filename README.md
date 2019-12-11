# SilentBell


SilentBell tem como objetivo ser uma campainha acessível para pessoas com deficiencia auditiva, é o trabalho final da disciplina Projeto Interdisciplinar, durante a gradução de Engenharia Biomédica (2019/2).

### Read Me
It's import to before commit those codes, make some changes:
### First, click [here](https://www.pushingbox.com/login.php) to create a login and follow a tutorial to create your own scenario in PushingBox

Then, in both codes in "Firmware" change:
* In the `<#define DEVD1>` line, paste the DeviceID of your scenario. Make sure you enclose it in quotes as shown.
* In the `<byte mac[] = { 0xAA, 0xAA, 0xAA, 0xAA, 0xAA, 0xAA }; IPAddress ip(111,111,111,111); >` line, be sure this address is unique in your network 
* And to found out whitch is your Ip and Mask, follow [this](http://www.howtofindmyipaddress.com/) tutorial.


### In this repository

* Docs: Resume write in portuguese about the project.

* Firmware: Arduino Codes.

* Images: Hardware for PCB creation.


## Development setup

* [PushingBox](https://www.pushingbox.com/) - server api used

* Libraries - All the used custom libraries could be found here, if you didn't found someone please contact me.

* Arduino IDE version 1.8.9



 > " THE BEERWARE LICENSE" (Revision 42):
Sofia Leal and Igor Henrique wrote - based in some free stuff found on internet-  this code. As long as you retain this
notice, you can do whatever you want with this stuff. If we
meet someday, and you think this stuff is worth it, you can
buy us a beer in return.
## Authors
* Sofia Leal - https://github.com/SofLeal - sofislealferreira@gmail.com
* Ana Flávia Notário -  flavia.notario@hotmail.com
* Igor Henrique Silva  - Igor.phnt@gmail



