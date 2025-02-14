![Logo](admin/shelly.png)

# ioBroker.shelly

[![NPM version](https://img.shields.io/npm/v/iobroker.shelly?style=flat-square)](https://www.npmjs.com/package/iobroker.shelly)
[![Downloads](https://img.shields.io/npm/dm/iobroker.shelly?label=npm%20downloads&style=flat-square)](https://www.npmjs.com/package/iobroker.shelly)
![Snyk Vulnerabilities for npm package](https://img.shields.io/snyk/vulnerabilities/npm/iobroker.shelly?label=npm%20vulnerabilities&style=flat-square)
![node-lts](https://img.shields.io/node/v-lts/iobroker.shelly?style=flat-square)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/iobroker.shelly?label=npm%20dependencies&style=flat-square)

![GitHub](https://img.shields.io/github/license/iobroker-community-adapters/iobroker.shelly?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/iobroker-community-adapters/iobroker.shelly/Test%20and%20Release?label=Test%20and%20Release&logo=github&style=flat-square)
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/iobroker-community-adapters/iobroker.shelly?label=repo%20vulnerabilities&logo=github&style=flat-square)

## Versions

![Beta](https://img.shields.io/npm/v/iobroker.shelly.svg?color=red&label=beta)
![Stable](http://iobroker.live/badges/shelly-stable.svg)
![Installed](http://iobroker.live/badges/shelly-installed.svg)

The adapter communicates with Shelly devices by REST API and the CoAP or MQTT protocol.    

Uses the default Shelly firmware (no flashing of firmware needed!). You will find more and detailed information about the device here : [Shelly](https://shelly.cloud/)

## Documentation

[🇺🇸 Documentation](./docs/en/README.md)

[🇩🇪 Dokumentation](./docs/de/README.md)

## Supported devices (Gen 1)

|Shelly Device|CoAP|MQTT|
|-------------|--------------|----|
|Shelly 1 (SHSW-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly 2 (SHSW-21/SHSW-22)|supported since v3.3.0|supported since v3.3.0|
|Shelly Bulb (SHBLB)|supported since v3.3.0|supported since v3.3.0|
|Shelly H&T (SHHT-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly Smoke (SHSM-01)|supported since v3.3.0|supported since v3.3.0|
|Shelly 1 1PM (SHSW-PM)|supported since v3.3.0|supported since v3.3.0|
|Shelly 2.5 (SHSW-25)|supported since v3.3.0|supported since v3.3.0|
|Shelly RGBW (SHRGBWW-01)|not supported since v3.4.0|not supported since v3.4.0|
|Shelly RGBW 2 (SHRGBW2)|supported since v3.3.0|supported since v3.3.0|
|Shelly2LED (SH2LED)|supported since v3.3.0|supported since v3.3.0|
|Shelly Plug (SHPLG-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly Plug S (SHPLG-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly Plug 2 (SHPLG-2)|supported since v3.3.0|supported since v3.3.0|
|Shelly Sense (SHSEN-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly 4 Pro (SHSW-44)|supported since v3.3.5|supported since v3.3.5|
|Shelly EM (SHEM)|supported since v3.3.0|supported since v3.3.0|
|Shelly Flood (SHWT-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly Dimmer (SHDM-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly Door/Window Sensor (SHDW-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly Bulb Duo (SHBDUO-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly 3EM (SHEM|supported since v3.3.0|supported since v3.3.0|
|Shelly Vintage (SHVIN-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly I3 (SHIX3-1)|supported since v3.3.0|supported since v3.3.0|
|Shelly Button (SHBTN-1)|supported since v3.3.3|supported since v3.3.3|
|Shelly Gas (SHGS-1)|supported since v3.3.3|supported since v3.3.3|
|Shelly Dimmer 2 (SHDM-2)|supported since v3.3.4|supported since v3.3.4|
|Shelly Door/Window Sensor 2 (SHDW-2)|supported since v3.3.5|supported since v3.3.5|
|Shelly Uni (SHUNI-1)|supported since v4.0.4|supported since v4.0.4|
|Shelly 1L (SHSW-L)|supported since v4.0.5|supported since v4.0.5|
|Shelly Color Bulb (SHCB-1)|supported since v4.0.5|supported since v4.0.5|
|Shelly Button (SHBTN-2)|supported since v4.0.5|supported since v4.0.5|
|Shelly Motion (SHMOS-01)|supported since v4.0.6|supported since v4.0.6|
|Shelly TRV (SHTRV-01)|supported since v6.0.0|supported since v6.0.0|

## Supported devices (Gen 2)

|Shelly Device|CoAP|MQTT|
|-------------|--------------|----|
|Shelly Plus 1 (shellyplus1)|---|supported since v5.0.0|
|Shelly Plus 1 PM (shellyplus1pm)|---|supported since v5.0.0|
|Shelly Plus 2 PM (shellyplus2pm)|---|supported since v5.2.0|
|Shelly Plus I4 (shellyplusi4)|---|supported since v5.3.0|
|Shelly Pro 1 (shellypro1)|---|supported since v5.2.0|
|Shelly Pro 1 PM (shellypro1pm)|---|supported since v5.2.0|
|Shelly Pro 2 (shellypro2)|---|supported since v5.2.0|
|Shelly Pro 2 PM (shellypro2pm)|---|supported since v5.2.0|
|Shelly Pro 4 PM (shellypro4pm)|---|supported since v5.0.0|

## Sentry

**This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers.** For more details and for information how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

## Troubleshooting after installation

### TypeError: xmlserializer.Builder is not a constructor
execute

`cd /opt/iobroker/node_modules/iobroker.shelly
npm install xml2js@0.4.23`

## Changelog

<!--
  Placeholder for the next version (at the beginning of the line):
  ### **WORK IN PROGRESS**
-->
### **WORK IN PROGRESS**
* (klein0r) Added mqtt status states and checks for generation 2 devices

### 6.0.0 (2022-07-07)
Important: The adapter now requires at least Node.js 14.5
* (klein0r) Added Shelly TRV (beta)
* (klein0r) Just publish data to Shelly device, if value changed
* (klein0r) **Breaking**: Configuration is only working in the new Admin 5 UI
* (klein0r) **Breaking**: Uptime is now a number (seconds since boot)
* (klein0r) Added channel names for Shelly 3EM
* (klein0r) Debug mode (MQTT) for Gen 2 devices
* (klein0r) Display total power for Shelly RGBW 2
* (klein0r) Save HTTP responses to file system for debugging (if enabled)
* (klein0r) Download scripts from generation 2 devices to files
* (klein0r) Optimized unload process to avoid errors
* (klein0r) Added device status states

### 5.3.2 (2022-03-06)
* (klein0r) Added cover position status for generation 2 devices
* (klein0r) Added cover power, voltage, current and energy for generation 2 devices
* (klein0r) Updated switch roles for material ui (switch.power to switch)

### 5.3.1 (2022-03-02)
* (klein0r) Don't ack new values directly after change

### 5.3.0 (2022-02-27)
* (klein0r) Added Shelly Plus I4
* (klein0r) Added more objects for power metering channels (current, voltage, limits, ...)
* (klein0r) Moved device temperature of generation 2 devices to relays (this is the official way)
* (klein0r) Added Sys channel (eco mode, timezone, ...) for generation 1 devices
* (klein0r) Fixed datatype error of Shelly 1/PM ext switch
* (klein0r) Added option to enable/disable WiFi access point (generation 2 devices)
* (klein0r) Added power limits and position control for covers (generation 2 devices)
* (klein0r) Removed colors for online state indication on device objects

### 5.2.0 (2022-02-16)
* (klein0r) Added Shelly Pro 1
* (klein0r) Added Shelly Pro 1 PM
* (klein0r) Added Shelly Pro 2
* (klein0r) Added Shelly Pro 2 PM
* (klein0r) Added Shelly Plus 2 PM
* (klein0r) Allow to change device and channel names of generation 2 devices
* (klein0r) Added auto on/off timers for generation 2 devices
* (klein0r) Added input mode, events and initial state for generation 2 devices
* (klein0r) Added support of covers / shutters for generation 2 devices
* (klein0r) Replaced node-fetch with axios (also for digest auth)

## License

The MIT License (MIT)

Copyright (c) 2018-2022 Thorsten Stueben <thorsten@stueben.de>,
                        Apollon77 <iobroker@fischer-ka.de> and
                        Matthias Kleine <info@haus-automatisierung.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
