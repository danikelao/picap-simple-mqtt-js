[![Bare Conductive](http://bareconductive.com/assets/images/LOGO_256x106.png)](http://www.bareconductive.com/)

# Bare Conductive Pi Cap Simple MQTT Utility

Example MQTT touch / release event sender code for the [Bare Conductive Pi Cap](http://www.bareconductive.com/shop/pi-cap/). Sends simple touch / release event messages to a specified MQTT broker. Based off an original example by Sven Haiges.

## Requirements

* Requires [WiringPi](http://wiringpi.com/) (`apt-get install wiringpi`)
* Requires [Bare Conductive's MPR121 libary for WiringPi](https://github.com/BareConductive/wiringpi-mpr121)
* Requires [Node.js](https://nodejs.org/en/) 6.7.0
* Requires [NPM](https://www.npmjs.com/)

## Install / Build

* You should install this code as part of the Pi Cap Raspbian package: `sudo apt-get install picap`    
* However, if you are doing this yourself, clone the repository and run `npm install && node ./simple-mqtt.js`

## Usage

    Usage: node simple-mqtt.js [OPTION]
    Options:
      -b, --broker  MQTT broker [REQUIRED]
          --help    displays this message

N.B. must be run as root    