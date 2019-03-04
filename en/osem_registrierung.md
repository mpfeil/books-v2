# Registration of a new senseBox {#head}

To register a new senseBox on openSenseMap, you need a user account. To get a new user account click on _Login_ and select _Sign up_.
Afterwards you find the _Dashboard_ under the user logo. You can use the _Dashboard_ to create new senseBoxes and [manage](osem_manage-boxes.md) them.

By clicking on _New senseBox_ the creation wizard will be openend and guide you through the registration process. The following specifications are required:

- **Name of your senseBox**: e.g. Phil´s box
- **Exposure**: used for filtering
- **Location**: can be set using the map
- **Model**: determines the sensor configuration

We offer different predefined models. Go and select it.
If you don´t have a predefined sensor configuration, you can specify your own sensor configuration by selecting _Manual configuration_. How this is done in detail visit the [other platform](osem_custom_sensor.md) guide.

After finishing the registration wizard, you get a Arduino Sketch which contains your selected sensor configuration and regularly reads the sensor values and transmit them to openSenseMap.
To transfer the Arduino Sketch to your senseBox the [Arduino IDE](https://www.arduino.cc/en/Main/Software) is required.
An exemplarly installation guideline for the _senseBox:home_ can be found [here](https://home.books.sensebox.de/de/software_installation.html)

## Advanced configuration

Besides the [HTTP REST API](osem_api.md) we also offer other interfaces for data transmisson. Settings can be found in the _Advanced_ section during the registration process or in the _Editing_ area for each senseBox.
Detailed guidelines can be found here:

- [MQTT](mqtt_client.md)
- [TheThingsNetwork](ttn_integration.md)
