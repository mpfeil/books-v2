# Manage boxes {#head}

Each registered user can manage any number of boxes on the openSenseMap.
If you want to change the settings of a box later or download the sketch, you can do this via the **Dashboard**.
This is available in the menu bar under the user icon as soon as a user is logged in:

<img src="https://raw.githubusercontent.com/sensebox/resources/master/images/osem_dashboard_btn.png" center width="150px" />

In the dashboard you can...

- [register new senseBoxes](osem_registrierung.md),
- edit existing senseBoxes or remove them,
- download Arduino Sketches for each senseBox

## Edit existing senseBox

Click on the _Edit_-Button of a senseBox in the dashboard. After that you are able to change different kind of settings.
After changes have been made in one of the sections, they are accepted by clicking on the disk symbol in the upper right corner.

> **_Note:_** *If the sensor configuration has been changed, the program code of the senseBox must also be updated in most cases. This can be found under the *Script* tab to copy it to the Arduino IDE. If the WiFi version of senseBox is used, the SSID and WiFi password in the sketch must be replaced again!*

## Delete a senseBox

If a senseBox is no longer used, or the measurements of this box are to be removed from the openSenseMap, it can be removed.
In the edit mode (see above) your current `PASSWORD` must be entered in the tab _General_ under the field "delete senseBox".
Afterwards a button appears under the field, by which the senseBox and its measurements are deleted.

> **_Attention:_** This removes the senseBox and all stored sensor data irrevocably! Since the measurements can also be valuable for a subsequent data evaluation, you should consider whether the senseBox should be deleted.
