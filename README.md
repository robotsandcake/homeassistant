# Home Assistant Config by [@RobotsandCake](https://github.com/robotsandcake) #

(This README and repository or a working progress and will be updated extensively next 24 to 48 hours.)

While reading these [YAML](http://yaml.org) configuration files for the home automation software [Home Assistant](https://home-assistant.io/), be aware that they are highly opinionated and have a definite skew towards people with motor skilled difficulties like mine.

If you want to know more about that, either through briefly on robots and cake 

This is a very opinionated configuration as they are heavily skewed towards being useful for people with motor skill disabilities like mine, although some of you able-bodied people will probably find useful here!  My quadriplegia has coloured by choices in which devices to automate and what they do when they are automated, for example I flash the lights throughout the house to summon help if I need it.

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

There are many ways to organise the large number of IoT Devices thatare scattered around myHumble abode, so I tried grouping them by manufacturer but that just looked odd after a while and didn't really make sense.  So now I am going to try dividing them up into their function, if it is super confusing please let me know so I can do nothing about it except cry.  Thanks.

