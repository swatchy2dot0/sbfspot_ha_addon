[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]
## ![SBFspot Logo](https://user-images.githubusercontent.com/1931158/30831762-006ec650-a249-11e7-86e3-13d01b36dd5d.jpg)

## ToDo List
### Fix
map directories to /addon/??

configure gui to SBFspot.cfg and SBFspotUpload.cfg??



### Configure 
built in MQTT conections??

built in MariaDB ( point to and add database and user in existing addon??


## ToDo end

SBFspot addon for supervised Home Assistant, based an open source project located at github ([SBFspot on github](https://github.com/SBFspot/SBFspot)).
This project creates an addon install for Home assistant users using the latest release of SBFspot as a docker install.

# Installation and configuration
Add ([this respository](https://github.com/HABuild/SBFspot_HA_addon)) to Home Assistant via the superviser > new respository menu > add respository

Fill in the config details to setup Inverter connection, Database, MQTT , and Upload API.

Start the addon

# ***Licence***
([MIT Licence](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt))

## SBFspot Readme ([SBFspot on github](https://github.com/SBFspot/SBFspot)).
![SBFspot Logo](https://user-images.githubusercontent.com/1931158/30831762-006ec650-a249-11e7-86e3-13d01b36dd5d.jpg)

Translation by Google: [[NL](https://translate.google.com/translate?act=url&depth=1&hl=nl&ie=UTF8&prev=_t&rurl=translate.google.com&sl=en&sp=nmt4&tl=nl&u=https://github.com/SBFspot/SBFspot)] - [[FR](https://translate.google.com/translate?act=url&depth=1&hl=nl&ie=UTF8&prev=_t&rurl=translate.google.com&sl=en&sp=nmt4&tl=fr&u=https://github.com/SBFspot/SBFspot)] - [[DE](https://translate.google.com/translate?act=url&depth=1&hl=nl&ie=UTF8&prev=_t&rurl=translate.google.com&sl=en&sp=nmt4&tl=de&u=https://github.com/SBFspot/SBFspot)] - [[ES](https://translate.google.com/translate?act=url&depth=1&hl=nl&ie=UTF8&prev=_t&rurl=translate.google.com&sl=en&sp=nmt4&tl=es&u=https://github.com/SBFspot/SBFspot)] - [[IT](https://translate.google.com/translate?act=url&depth=1&hl=nl&ie=UTF8&prev=_t&rurl=translate.google.com&sl=en&sp=nmt4&tl=it&u=https://github.com/SBFspot/SBFspot)]
### **Introduction**
SBFspot, formerly known as SMAspot, is an open source project to get actual and archive data out of an SMA® inverter over Bluetooth or Ethernet (Speedwire®) It works on either Linux ([Raspberry Pi](http://www.raspberrypi.org)) and Windows.

### **What it does**
SBFspot connects via Bluetooth or Ethernet to your SMA® solar/battery inverter and reads Archive Day/Month Power generation, user/installer events and the actual (spot) data. The collected data is stored in a SQL database (SQLite/MySQL/MariaDB) or SMA® compatible .csv files.
A separate service/daemon uploads the collected data to [PVoutput.org](https://pvoutput.org)

### **Known bugs and limitations**
For a list of known bugs, consult the [issues](https://github.com/SBFspot/SBFspot/issues). If you find a bug, please create an [issue](https://github.com/SBFspot/SBFspot/issues).

### **Documentation**
Refer to the [Wiki](https://github.com/SBFspot/SBFspot/wiki) for documentation and FAQ.

### **Special thanks to:**
* S. Pittaway: Author of ["NANODE SMA PV MONITOR"](https://github.com/stuartpittaway/nanodesmapvmonitor) on which this project is based.
* W. Simons : Early adopter, main tester and SMAdata2® Protocol analyzer
* G. Schnuff : SMAdata2® Protocol analyzer
* T. Frank: Speedwire® support
* Snowmiss: User manual
* All other users for their contribution - in any form - to the success of this project

### **Donations**
SBFspot is a free tool, developed during personal free time. If you like it, consider a donation.
If you click on the button below, you will be taken to the secure PayPal Web site. You don't need to have a paypal account in order to make a donation.

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3R5JSRCXBGSLQ)

### **License**
[Attribution - NonCommercial - ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode)

In short, you are free:
* to Share => to copy, distribute and transmit the work
* to Remix => to adapt the work
Under the following conditions:
* **Attribution:** You must attribute the work in the manner specified by the author or Licensor (but not in any way that suggests that they endorse you or your use of the work).
* **Noncommercial:** You may not use this work for commercial purposes.
* **Share Alike:** If you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.

### **Disclaimer**
A user of SBFspot software acknowledges that he or she is receiving this software on an "as is" basis and the user is not relying on the accuracy or functionality of the software for any purpose. The user further acknowledges that any use of this software will be at his own risk and the copyright owner accepts no responsibility whatsoever arising from the use or application of the software.

SMA, Speedwire are registered trademarks of [SMA Solar Technology AG](http://www.sma.de/en/company/about-sma.html)

[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20testing-red.svg
[release-shield]: https://img.shields.io/badge/version-v0.0.1-blue.svg
[release]: https://github.com/hassio-addons/addon-ssh/tree/v0.0.1
