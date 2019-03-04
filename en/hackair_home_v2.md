# Connect hackAIR home sensor v2 to openSenseMap.org {#head}

It is possible to connect the HackAIR home Sensor (Version 2) to openSenseMap.

First of all you have to assemble your [hackAIR Sensor](http://www.hackair.eu/hackair-home-v2/) and use the
[hackair-v2-advanced](https://github.com/mkraats/hackair-v2-advanced).

Afterwards the openSenseMap configuration should be available in the web interface. ([Fig. 1](#figure-1-webinterface-hackair))

After that register a new senseBox on openSenseMap with the correct selected hardware.

## 1. [New senseBox](https://opensensemap.org/register)

- Fill in location, exposure and name.
- Under **Hardware** unfold **hackAIR** and select the correct sensor configuration ([Fig. 2](#figure-2-registration-opensensemap))
- Finish the registration
- **Important:** copy the _senseBox ID_. This is a 24 charachter long string and looks like this: _58a88c6b650831d8a3625e01_
- If you have signed up with an existing mail address you get an mail containing your senseBox-ID

## 2. Configure hackAIR device

The `hackAIR home v2` Sensor can be configured via a web interface. To do so plug in your device and an open WiFi network with the name `ESP-wemos` should appear. After that you have to do the following steps:

- Open up the web interface in a browser (http://192.168.4.1)
- Under **Configure WiFi** fill in the _senseBox-ID_ inside **openSenseMap senseBox ID**
- Under **Configure WiFi** fill in the _access token_ inside **senseBox access token**
- At the bottom of the page click **Save**

## Ready

The `hackAIR home v2` Sensor is configured and should send data to openSenseMap.

## Figure 1: Webinterface HackAIR

<img src="https://github.com/sensebox/resources/raw/master/images/hackair/02_Sensor_Konfiguration.png"/>

## Figure 2: Registration openSenseMap

<img src="https://github.com/sensebox/resources/raw/master/images/hackair/01_openSenseMap_Konfiguration.png"/>
