# Mocc

Mocc (My Own Camper Control) is a collection of tools to automate and monitor as much as possible in our Camper / RV / Mobilehome / whatever name it has in your region ;-) 

## Hardware
The system is going to be build around a central Raspberry Pi with a lcd touch screen, that can be located in the kitchen area.

A second Raspberry Pi, also with a lcd touch screen, is going to be the replacement of the rearview mirror. 

To let everything work together and have it send updates to my smartphone, I'm going to use a five port netgear switch connected to a 3G mobile router.

All sensors and switches are going to be connected to [esp8266](https://en.wikipedia.org/wiki/ESP8266) microchips

Sensors to be used:
* [Victron smart shunt](https://www.victronenergy.com/battery-monitors/smart-battery-shunt)
To be used to monitor both the houdehold and starter battery voltage and household battery amp usage

* more to come...

## Systems eplained

### Central Pi
The central pi is going to be placed in the kitchen of our Camper. This way it can replace the current control board with all the switches.

More to come, but lack of time for now ;-)

### Rearview Pi
Since the rearview mirror has no use at this moment, we are allowed to remove it, so we decided to replace it with a second Raspberry Pi and put a camera on the back of the Camper to use it as a rearview mirror.

More to come, but lack of time for now ;-)

### Battery monitor
The battery monitor is going to be build with an esp8266, connected to the Victron smart shunt. This way we can monitor the battery life, when the Camper is in storage. When we measure, the esp8266 will then go in deep sleep, to wake up again after some (need to be determined) hours, then measure again. Once a day it will power the mobile router, with a relay, and upload the collected data of that day.


## Contributing
Pull requests are more than welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
