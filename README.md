[Tonino Firmware](https://github.com/myTonino/Tonino-Firmware)
===============

Open-Source Arduino firmware for the [Tonino Color Meter](http://my-tonino.com)

![](img/tonino-flow-chart.png?raw=true)

Build Tonino-Firmware
---------------------

To build the PlatformIO project for the Tonino-Firmware, follow these steps:

1. **Clone the Repository:**
   Open a terminal and clone the repository:
   ```sh
   git clone https://github.com/fvdbeek/Tonino-Firmware.git
   cd Tonino-Firmware
   ```

2. **Install PlatformIO:**
   If you don't already have PlatformIO installed, you can install it using pip:
   ```sh
   pip install platformio
   ```

   Alternatively, you can install PlatformIO as a VSCode extension.

3. **Build the Project:**
   Navigate to the project directory and run the following command to build the project:
   ```sh
   pio run
   ```

4. **Upload the Firmware:**
   Connect your device and upload the firmware using:
   ```sh
   pio run --target upload
   ```

5. **Monitor the Serial Output (Optional):**
   To monitor the serial output, use:
   ```sh
   pio device monitor
   ```

These instructions should help you build and upload the firmware for the Tonino Color Meter using PlatformIO. If you encounter any issues, refer to the [PlatformIO documentation](https://docs.platformio.org/en/latest/) for more detailed information.

Tonino Resources
----------------
- [Tonino site](http://my-tonino.com)
- [Tonino app](https://github.com/myTonino/Tonino-App)
- [Tonino firmware](https://github.com/myTonino/Tonino-Firmware)
- [Tonino serial protocol](https://github.com/myTonino/Tonino-Firmware/blob/master/Tonino-Serial.md)
- [Tonino hardware](https://github.com/myTonino/Tonino-Hardware)

Version History
---------------

- v1.1.8 Change to platformio platform
- v1.1.7 Increases stability
- v1.1.6 Adds automatic averaging
- v1.1.5 Calibration stability improved
- v1.1.4 App alignment
- v1.1.3 Increased stability
- v1.1.2 Increased stability for calibration and EEPROM storage
- v1.0.8 Improved calibration stability
- v1.0.7 Improved external light suppression
- v1.0.6 Adds UP notification during calibration
- v1.0.5 Internal update
- v1.0.4 Buggy initial release

License
-------

[![](http://upload.wikimedia.org/wikipedia/commons/4/42/License_icon-bsd-88x31.png)](LICENSE?raw=true)
