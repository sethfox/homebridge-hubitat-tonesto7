## v2.0.0

- [NEW] **_Important NOTICE:_**
  
  - **Due to the changes in the plugin API you can not directly update the plugin from v1, you will need to add as a new accessory and setup your devices/automations/scenes again.
  On a positive note, you can use your existing hubitat app instance as long as you update it to the latest code.**

- [NEW] Completely rewrote the entire plugin from the ground up using modern javascript structure.
- [NEW] The code is now much cleaner, easier to update/maintain, and easier for others to follow.
- [NEW] The plugin is now faster, leaner, and way more stable than the previous versions.
- [NEW] The plugin now uses the Homebridge Dynamic platform API, meaning it no longer requires a restart of the Homebridge service for device changes to occur.
- [NEW] The plugin now utilizes the device cache on service restart to prevent losing all of your devices when the plugin fails to start for an extended period of time.
- [NEW] Plugin will now remove devices no longer selected under Hubitat App.
- [NEW] Logging system was rewritten to provide more insight into issues and status, as well as write them to a file.
- [NEW] Switched web request library from Request-Promise to Axios.
- [FIX] StatusActive characteristic now reports correctly.
- [NEW] Added support for bringing acceleration sensors into homekit as motion sensors.
- [FIX] Lot's of fixes for device state updates and device commands.
- [FIX] Added support for AirPurifier & AirQuality (@danielskowronski)
- [FIX] Delays on device event updates resolved.
- [FIX] Thermostat Mode fixes (@torandreroland)
- [NEW] Many, many other bug fixes for devices, commands and many other items.