# Noldus Information Technology Firmware flasher

Web tool to install firmware on Noldus devices via the browser using WebSerial.

## Used by

- DanioVision Observation Chamber 0050 (unreleased)
- DanioVision Temperature Control Unit 0020 (unreleased)

## Local development

- Clone this repository.
- Run `script/develop`
- Open http://localhost:5004/

or:
 - Run a Python HTTP server with `python -m http.server 5004` in the root folder. 
## Origin

This project was originally written by [Melissa LeBlanc-Williams](https://github.com/makermelissa). [Nabu Casa](https://www.nabucasa.com) ported the code over to TypeScript and in March 2022 took over maintenance from Adafruit. In July 2022, the Nabucasa stopped maintaining the project in favor of an official, but very early release of Espressif's [esptool-js](https://github.com/espressif/esptool-js/). Due to the instability of the tool, Adafruit updated their fork with Nabucasa's changes in November 2022 and took over maintenance once again.

In December 2024, after the official Espressif tool had become more stable, the tool was once again updated to use Espressif's [esptool-js](https://github.com/espressif/esptool-js/) as the backend while maintaining the familiar frontend of the original tool. This allows for retaining a familiar interface, which is also used in the guides, to remain in place while also keeping current on the latest board releases.
