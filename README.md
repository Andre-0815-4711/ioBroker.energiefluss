![Logo](admin/energiefluss.png)

# ioBroker.energiefluss

[![NPM version](https://img.shields.io/npm/v/iobroker.energiefluss?style=flat-square)](https://www.npmjs.com/package/iobroker.energiefluss)
[![Downloads](https://img.shields.io/npm/dm/iobroker.energiefluss.svg)](https://www.npmjs.com/package/iobroker.energiefluss)
![Number of Installations](https://iobroker.live/badges/energiefluss-installed.svg)

![GitHub](https://img.shields.io/github/license/SKB-CGN/iobroker.energiefluss?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/SKB-CGN/iobroker.energiefluss?logo=github&style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/SKB-CGN/iobroker.energiefluss?logo=github&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/SKB-CGN/iobroker.energiefluss?logo=github&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/SKB-CGN/iobroker.energiefluss?logo=github&style=flat-square)

[![NPM](https://nodei.co/npm/iobroker.energiefluss.png?downloads=true)](https://nodei.co/npm/iobroker.energiefluss/)

**Tests:** ![Test and Release](https://github.com/SKB-CGN/ioBroker.energiefluss/workflows/Test%20and%20Release/badge.svg)

## Energiefluss adapter for ioBroker

Es stellt einen animierten Energiefluss fuer Photovoltaik, Batterie, Hausverbrauch, Einspeisung und Auto-Ladung bereit.

## Installation
Installation ueber die Github Katze in ioBroker moeglich

## Support
Wenn Dir meine Arbeit gefaellt und Du mich unterstuetzen moechtest, so kannst Du dies hier tun:
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.me/StephanKreyenborg)

## Changelog
<!--
	Placeholder for the next version (at the beginning of the line):
	### **WORK IN PROGRESS**
-->

### **WORK IN PROGRESS**
- Added "Consumption negativ" option
- Choose Number of places after the decimal point for Values
- Function, to Display the netto house consumption (if car and additional equipment is also used)
- Show or hide shadow around the circles
- Thickness of the circle outline (in px)
- instances link corrected
- multiple instances can be accessed via the link -> http://<IP>/energiefluss/?instance=<Instance>
- Corrected getting the WebPort, if not on standard 8082
- added "WebApp" functionality on Android, iOS, Apple and Microsoft Browsers - If opened via Homescreen, the page shows without address-bar
- added shortcut icons
- changed adapter picture
- fixed some bugs for displaying HTML elements

### 0.6.0 (2022-07-29)
- option, to add a custom circle feeded from the house (free text and icon)
- own fonts can be added through download parameter - must be in the same domain or ip
- Added 3 new Icons for Accu-state (0%, 25%, 75%, >75%)

### 0.5.1 (2022-07-27)
- added posibility, to change battery charging and discharging direction

### 0.5.0 (2022-07-27)
- Fill inside the circle configurable
- line color configurable
- line animation configurable

### 0.4.1 (2022-07-26)
- fixed JSON Object with configuration

### 0.4.0 (2022-07-26)
- Rewrote most of the Code, to add more flexibility
- changed Data-Store to States instead of in memory (faster rendering)
- Line Size can be adjusted
- 'Stucking' while value has changed is removed, as rendering will be done on the fly
- more stable
- some bugs fixed (battery State)

### 0.3.1 (2022-07-22)

- added font-size options in admin
- added font-face options in admin
- addded smoother animation

### 0.2.6 (2022-07-15)
- fixed different states for battery charging

### 0.2.5 (2022-07-14)
- fixed number rounding
- fixed for positive values for consuming and grid-feeding

### 0.2.4 (2022-07-01)
- fixed Tranlastions

### 0.2.3 (2022-07-01)
- fixed a crash, which might occur, if the state got deleted

### 0.2.2 (2022-06-24)
- fixed failed log output

### 0.2.0 (2022-06-24)
- Added new State for car charger connected and color option

### 0.2.0-0 (2022-06-24)
- added possibility for changing the colors (text and circles)

### 0.0.22 (2022-06-21)
- implemented function, to calculate house consumption, if no house-consumption state is available

### 0.0.21 (2022-06-17)
- corrected admin Tab

### 0.0.20 (2022-06-17)
- changed alignment if no battery is present to save space on the left

### 0.0.19 (2022-06-17)
- changed alignment of View (height and width are not dynamically sized)
- support for transparent background, if loaded in iframe
- changed incompatible TAG in HTML

### 0.0.17 (2022-06-16)
- fixed solar and grid line animation

### 0.0.16 (2022-06-15)
- Fixed uncaught Error
- Changed translation for checkbox in admin

### 0.0.13 (2022-06-15)
- Added checkbox for reversing Grid-feed and Grid-consuming

### 0.0.12 (2022-06-15)
- added line animation

### 0.0.11 (2022-06-15)
- fixed some bugs

### 0.0.3 (2022-06-14)
* fixed some bugs

### 0.0.2 (2022-06-14)
* initial release

## License
MIT License

Copyright (c) 2022 SKB <info@skb-web.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
