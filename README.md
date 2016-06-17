Back in 2011 I found this kickstarter for a project called the InkShield. It’s an Arduino shield that drives a single black inkjet cartridge for manual operation. It was a very well done kickstarter and the hardware was made opensource, if you want to build one yourself you can do so using the project files.

Original kickstarter:
http://www.kickstarter.com/projects/1908026860/inkshield-an-open-source-inkjet-shield-for-arduino

All the InkShield source files (PCB, schematics, sample code, etc):
https://github.com/NicholasCLewis/InkShield

So I backed the kickstarter and got one of these shields and made it into a complete project for myself. It’s a lot of fun, you can inkjet-print on any surface with this device.

This repo is my modified Arduino InkShield code which gives me 5 different messages I can select to print. To change the messages just modify the code and re-upload to the Arduino. My code requires one analog input on the Arduino for the resistor network. You will need to modify the code for the resistor values you use in your circuit. I borrowed code from this forum post example:
http://www.arduino.cc/cgi-bin/yabb2/YaBB.pl?num=1226896251

Thanks!
