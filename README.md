# Home Assistant Config by [@RobotsandCake](https://github.com/robotsandcake) #

This README and repository are a work in progress. These [YAML](http://yaml.org) [Home Assistant](https://home-assistant.io/) configuration files are designed for people withprofound motor-skill difficulties like mine. For example I can flash the lights different colours throughout the houseto summon help if I need it, so blue flashing means "hey, I could do with a hand" whereas red flashing light means "Run come quick, my hair is on fire!". 

Some of you able-bodied people might find some use in the things here, and you are also welcome.

## Hardware ##

I use an old [Mac Mini (2011)](https://support.apple.com/kb/sp632?locale=en_US). It doesn't really have the grunt to run the most recent macOS properly, but it's absolutely perfect for running Home Assistant. It's been up for couple of years now and has barely crashed.

### Operating System ###

After about twelve minutes of very serious thought, I decided that [Ubuntu 18.04 LTS (Bionic Beaver) Server](http://releases.ubuntu.com/18.04/) was the best operating system to fit my needs. If you want to work out which  flavour of Linux you are running just fire up a terminal and issue the command: `lsb_release -a`

``` bash
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 18.04.4 LTS
Release:        18.04
Codename:       bionic
```

Note the letters [LTS](https://wiki.ubuntu.com/LTS) after the version name and number on the above Description line, as per the Ubuntu wiki the letters LTS fund for long-term support. What that means to us is that the one to release new versions of the operating every 6 months, and they promised to keep the versions updated for that amount of time however the LTS versions are focused at the enterprise customers and are guaranteed as much as they possibly can to work for at least 2 years into the future.

(This is my understanding of the system anyway, please feel free to put me right if I have made a mistake!)

One of the main reasons I went with the Long-Term Support (LTS) version was that I do not need the latest and greatest version of the operating system with all of the new fancy bells and whistles, as this was going to running my house stability was the most important thing to me. Hence my going with the [Ubuntu](https://ubuntu.com/)  version of their server software.

There is also the fact that there is a huge community around 12 meaning that any problems you run into have almost certainly been encountered before and a solution will almost certainly be available on Stack overflow. Except how to quit out of Vim[^vim]!

## Software ##

[Home Assistant](https://home-assistant.io/) is the most important piece of software in my Home automation set up. It's the central hub that glues together all of the disparate Internet of Things (IoT) devices that wouldn't ordinarily be compatible with each other. There are components for everything. 

## Devices ##

There are many ways to organise the large number of IoT Devices thatare scattered around my Humble abode, so I tried grouping them by manufacturer but that just looked rather odd after a while and wouldn't really make sense.  If it is super confusing please let me know so I can do nothing about it except cry.  Thanks.

---

[^vim]: I don't see what is so difficult, press escape then type a colon  followed by the Q and press return. Simples!

## IoT Devices in Use: ##

These are the Internet of Things (IoT) devices that make up my home automation network.

<details>
<summary>Digital Assistants</summary> 
- [Google Home](https://store.google.com/gb/product/google_home)
- - [Echo Dot Gen 2](http://amzn.to/2hvCexj)
- [Google Home Mini](https://store.google.com/gb/product/google_home_mini)
</details>

<details>
<summary>Various Z-Wave Devices</summary>
- [AEON Aeotec Z-Stick Gen5 - Z-Wave Plus USB Gateway](https://www.amazon.co.uk/AEON-AEOEZW090-C-Aeotec-Z-Stick-gateway/dp/B00YETCNOE)
- [FOXX FPZWRE1UK Z-Wave Range Extender](https://www.amazon.co.uk/gp/product/B014JS4T0A/ref=oh_aui_search_detailpage?ie=UTF8&th=1)
- [FOXX FPZWSSG5UK Z-Wave Smart Switch/Power Outlet](https://www.amazon.co.uk/gp/product/B014JS57XI/ref=oh_aui_search_detailpage?ie=UTF8&th=1)
- [Z-Wave Plus Aeotec Smart Switch 6](https://www.vesternet.com/z-wave-aeon-labs-smart-switch-6-gen5-uk)
- [Fibaro FGMS-001 Motion Sensors](https://www.fibaro.com/en/products/motion-sensor/)
- [Z-Wave Plus Aeotec Door/Window Sensor 6](https://www.vesternet.com/z-wave-aeon-labs-door-window-sensor-6-gen5) 
- [Aeotec Door / Window Sensor 7](https://aeotec.com/z-wave-door-window-sensor/)
</details>

<details>
<summary>Google Products</summary> 
- [Google Nest Protect 2nd Generation Smoke + Carbon Monoxide Alarm (Wired), White](https://store.google.com/gb/product/nest_protect_2nd_gen)
- [Chromecast Audio](https://store.google.com/product/chromecast_audio)
</details>


