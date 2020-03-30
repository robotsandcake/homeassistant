# Home Assistant Config by [@RobotsandCake](https://github.com/robotsandcake) #

(This README and repository is very much a work in progress, check back often for updates.)

(This readme and repository is very much a work in progress, check back often as it will be updated a lot in the next 24 hours)

These are my [Home Assistant](https://home-assistant.io/) [YAML](http://yaml.org) configuration files. This is a very opinionated configuration as they are heavily skewed towards being useful for people with motor skill disabilities like mine, although some of you able-bodied people will probably find useful here!  My quadriplegia has coloured by choices in which devices to automate and what they do when they are automated, for example I flash the lights throughout the house to summon help if I need it.

## Slight Caveat ##

These are my [Home Assistant](https://home-assistant.io/) [YAML](http://yaml.org) configuration files. I am quadriplegic.  The settings will be useful to other people with motor skill disabilities.  They may also be useful to other people. For example, I flash the lights throughout the house to summon help if I need it.

## Hardware ##

The centre of my home automation set up is a [Mac Mini (2011)](https://support.apple.com/kb/sp632?locale=en_US). It doesn't really have the grunt to run the most recent macOS properly, but it's absolutely perfect for running Home Assistant. It's been up for over a year without crashing and the hardware is just lovely.

--

The centre of my home automation set up is a [Mac Mini (2011)](https://support.apple.com/kb/sp632?locale=en_US). It doesn't really have the grunt to run the most recent macOS properly, but it's absolutely perfect for running Home Assistant. It's been up for over a year without crashing and the hardware is just lovely.

## Software ##


### Operating System

Operating System [Ubuntu 18.04 LTS (Bionic Beaver) Server](http://releases.ubuntu.com/18.04/) as the base for the entire system. I chose this version for it's the Long-Term Support (LTS) version which means it will get updates into the future, and it's very well supported with a large community surrounding [Ubuntu](https://ubuntu.com/) which makes diagnosing and solving problems that much easier.



Operating System [Ubuntu 18.04 LTS (Bionic Beaver) Server](http://releases.ubuntu.com/18.04/) as the base for the entire system. I chose this version for it's the Long-Term Support (LTS) version which means it will get updates into the future, and it's very well supported with a large community surrounding [Ubuntu](https://ubuntu.com/) which makes diagnosing and solving problems that much easier.

### Home Assistant (The Linchpin)

[Home Assistant](https://home-assistant.io/) is the most important piece of software in my Home automation set up. It's the central hub that glues together all of the disparate Internet of Things (IoT) devices that wouldn't ordinarily be compatible with each other. There are components for everything. 

---

[Home Assistant](https://home-assistant.io/) is the most important piece of software in my Home automation set up, it's the central hub that glues together all of the disparate Internet of Things (IoT) devices that wouldn't ordinarily be compatible with each other. There are components for everything from 


## Devices ##

There are many ways to organise the large number of IoT Devices thatare scattered around myHumble abode, so I tried grouping them by manufacturer but that just looked odd after a while and didn't really make sense.  So now I am going to try dividing them up into their function, if it is super confusing please let me know so I can do nothing about it except cry.  Thanks.  :-)

### Raspberry Pi ###

- [1.7 MILLION CRAP TONNES OF RASPBERRY PIS, natch](https://raspberrypi.org)

### Sensors ###

[Nest Protect 2nd Generation Smoke + Carbon Monoxide Alarm (Wired)](https://www.amazon.co.uk/Nest-Protect-Generation-Carbon-Monoxide/dp/B00ZC5FJ40/ref=sr_1_1?keywords=Google%2C+S3003LWES%2C+Nest+Protect+Smoke+Carbon+Monoxide+Alarm%2C+2nd+Gen%2C+Wired&linkCode=gs3&linkId=5b76efadac409f4d65779d912ded37df&qid=1582500124&s=diy&sr=1-1)


### Inputs ###

- [Flic Wireless Smart button](https://flic.io/)


### Controlled by Voice ###

- [Fibaro FGMS-001 Motion Sensors](https://www.fibaro.com/en/products/motion-sensor/)
- [Flic Wireless Smart button](https://flic.io/)
- [Echo Dot Gen 2](http://amzn.to/2hvCexj)

### Speakers ###

- [Chromecast Audio](https://store.google.com/product/chromecast_audio)
- [Google Home](https://store.google.com/gb/product/google_home)
- [Google Home Mini](https://store.google.com/gb/product/google_home_mini)

- [Z-Wave Plus Aeotec Door/Window Sensor 6](https://www.vesternet.com/z-wave-aeon-labs-door-window-sensor-6-gen5) 
- [Aeotec Door / Window Sensor 7](https://aeotec.com/z-wave-door-window-sensor/)
- [Z-Wave Plus Aeotec Smart Switch 6](https://www.vesternet.com/z-wave-aeon-labs-smart-switch-6-gen5-uk)
- [AEON Aeotec Z-Stick Gen5 - Z-Wave Plus USB Gateway](https://www.amazon.co.uk/AEON-AEOEZW090-C-Aeotec-Z-Stick-gateway/dp/B00YETCNOE)

### LIGHTS ###

- [LIFX Light bulbs](https://uk.lifx.com/products/lifx)


- [FOXX FPZWRE1UK Z-Wave Range Extender](https://www.amazon.co.uk/gp/product/B014JS4T0A/ref=oh_aui_search_detailpage?ie=UTF8&th=1)
- [FOXX FPZWSSG5UK Z-Wave Smart Switch/Power Outlet](https://www.amazon.co.uk/gp/product/B014JS57XI/ref=oh_aui_search_detailpage?ie=UTF8&th=1)

### Generic Z-Wave ###



### Cameras ###

- [Mobotix T25 Outdoor Station and Access Module](https://www.mobotix.com/en/products/access-control/t25-outdoor-station-access-module)


### Networking ###

- [Fingbox](https://www.fing.io/fingbox-network-security-appliance/)

## IoT Devices in Use:

- [Nest Protect - 2nd Gen (Wired)](https://www.amazon.co.uk/Nest-Protect-Generation-Monoxide-Battery/dp/B00ZC5FJ40/ref=sr_1_1?ie=UTF8&qid=1496760920&sr=8-1&keywords=nest%2Bprotect&th=1)
- [Echo Dot Gen 2](http://amzn.to/2hvCexj)
- [Flic Wireless Smart button](https://flic.io/)
- [Chromecast Audio](https://store.google.com/product/chromecast_audio)
- [Google Home](https://store.google.com/gb/product/google_home)
- [Google Home Mini](https://store.google.com/gb/product/google_home_mini)
- [AEON Aeotec Z-Stick Gen5 - Z-Wave Plus USB Gateway](https://www.amazon.co.uk/AEON-AEOEZW090-C-Aeotec-Z-Stick-gateway/dp/B00YETCNOE)
- [FOXX FPZWRE1UK Z-Wave Range Extender](https://www.amazon.co.uk/gp/product/B014JS4T0A/ref=oh_aui_search_detailpage?ie=UTF8&th=1)
- [FOXX FPZWSSG5UK Z-Wave Smart Switch/Power Outlet](https://www.amazon.co.uk/gp/product/B014JS57XI/ref=oh_aui_search_detailpage?ie=UTF8&th=1)
- [Z-Wave Plus Aeotec Smart Switch 6](https://www.vesternet.com/z-wave-aeon-labs-smart-switch-6-gen5-uk)
- [Fibaro FGMS-001 Motion Sensors](https://www.fibaro.com/en/products/motion-sensor/)
- [Z-Wave Plus Aeotec Door/Window Sensor 6](https://www.vesternet.com/z-wave-aeon-labs-door-window-sensor-6-gen5) 
- [Aeotec Door / Window Sensor 7](https://aeotec.com/z-wave-door-window-sensor/)
- [LIFX Light bulbs](https://uk.lifx.com/products/lifx)
- [Mobotix T25 Outdoor Station and Access Module](https://www.mobotix.com/en/products/access-control/t25-outdoor-station-access-module)
- [Fingbox](https://www.fing.io/fingbox-network-security-appliance/)
- [1.7 MILLION CRAP TONNES OF RASPBERRY PIS, natch](https://raspberrypi.org)
- [Gammu](https://wammu.eu/gammu/)