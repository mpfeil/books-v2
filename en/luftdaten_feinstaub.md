# Connect Luftdaten.info Airrohr to openSenseMap.org {#head}

It is possible to connect Luftdaten.info Airrohr devices and transmit the sensor values to openSenseMap. To transmit the data to openSenseMap first of all you have to figure out what kind of sensors are connected to your Airrohr device. The easiest way is to connect to the web interface of your device ([Fig. 1](#figure-1-webinterface-airrohr))

Afterwards you have to register a new senseBox with the looked up sensor configuration on openSenseMap. If you select the wrong sensor configuration during the registration, the easiest way is to delete the senseBox and register a new one with the correct configuration.

## 1. [New senseBox](https://opensensemap.org/register)

- Fill in location, exposure and name.
- Under **Hardware** unfold **luftdaten.info** and select the correct sensor configuration ([Fig. 2](#figure-2-registration-opensensemap))
- Finish the registration
- **Important:** copy the _senseBox ID_. This is a 24 charachter long string and looks like this: _58a88c6b650831d8a3625e01_
- If you have signed up with an existing mail address you get an mail containing your senseBox-ID

## 2. Configure Airrohr device

The Airrohr device can be configured via a web interface. Therefore connect to the WiFi of your Airrohr device and open up the web interface within a browser of your choice.

- Open up the web interface of your Airrohr device
- Under **Weitere APIs** check the checkbox **An openSenseMap senden**. Fill in the _senseBox-ID_
- Click on **Speichern** at the bottom of the page

## Ready

The Airrohr configuration is now finished and should transmit data to openSenseMap.

## Figure 1: Webinterface Airrohr

<img src="https://github.com/sensebox/resources/raw/master/images/luftdaten/02_Sensor_Konfiguration.png"/>

## Figure 2: Registration openSenseMap

<img src="https://github.com/sensebox/resources/raw/master/images/luftdaten/01_openSenseMap_Konfiguration.png"/>
