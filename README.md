# ESP8266  HomeKit Paradox Alarm System
ESP8266  HomeKit server for Paradox Alarm Systems


------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-Paradox-Alarm-System/total?color=green)](https://github.com/HomeKidd/ESP8266-HomeKit-Paradox-Alarm-System/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-Paradox-Alarm-System?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-Paradox-Alarm-System/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>

# Still in development, the first release is just an "empty" HomeKit Security System accessory!!!

## For More information and Supported Devices please read the [Wiki page](https://github.com/HomeKidd/ESP8266-HomeKit-Paradox-Alarm-System/wiki/Build-Instructions)!

**Features:**

* Arming Paradox Security Systems
* Disarming Paradox Security Systems
* Night Arm for Paradox Security Systems
* Away Arm for Paradox Security Systems
* Alarm notifications _(via HomeKit)_
* Low Battery notification (_backup battery faillure)_
* ~~Tampered state~~
* Custom Setup Page _(with encryption)_
* Custom PCB for connecting ESP8266 to Paradox control panel _(12V serial)_
* Reset button

**Zones and Motion/Door sensers are not supported due to ESP8266 isn't powerful to handle 32 accessories at once!!!**


**Demo:**

<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Paradox-Alarm-System/raw/master/images/paradox_demo.PNG" width="650"/> </br>
</br>


This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2019 Apple Inc. All rights reserved.
