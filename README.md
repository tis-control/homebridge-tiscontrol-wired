<span align="center">

<h1>
<p align="center">

<img src="https://github.com/TISControl/homebridge-tiscontrol-wired/blob/master/logo.png" width="200">

</p>
  <br />
  <p align="center">
  Homebridge TIS Control Limited
  </p>
</h1>

[![npm downloads](https://badgen.net/npm/dt/homebridge-tiscontrol-wired?color=purple)](https://www.npmjs.com/package/homebridge-tiscontrol-wired)
[![npm version](https://badgen.net/npm/v/homebridge-tiscontrol-wired?color=purple)](https://www.npmjs.com/package/homebridge-tiscontrol-wired)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/tiscontrol/homebridge-tiscontrol-wired.svg)](https://github.com/tiscontrol/homebridge-tiscontrol-wired/pulls)
[![GitHub issues](https://img.shields.io/github/issues/tiscontrol/homebridge-tiscontrol-wired.svg)](https://github.com/tiscontrol/homebridge-tiscontrol-wired/issues)

Unofficial [Homebridge](https://homebridge.io) plugin for [TIS Control Wired](https://www.tiscontrol.com/tptis/en/index.html), allowing you to control your TIS Smart Home devices with [Apple Home](https://www.apple.com/ios/home/).

</span>

## 🔄 Supported Devices

Homebridge TIS currently supports these devices through a TIS BUS or Zigbee hub:

-  Appliance
-  Curtain Motor
-  Dimmer
-  Fan 
-  Floor Heater
-  Mood
-  RGB
-  Relay To Curtain
-  Switch
-  Thermostat


If you have another device connected to TIS and would like to see it supported in this plugin, please open a [device request](https://github.com/tiscontrol/homebridge-tiscontrol-wired/issues/new?assignees=&labels=enhancement,new%20device&template=device-request.md&title=New%20device:) issue.

## Installation

[Install Homebridge](https://github.com/homebridge/homebridge/wiki), add it to [Apple Home](https://github.com/homebridge/homebridge/blob/master/README.md#adding-homebridge-to-ios), then install and configure Homebridge TIS.

### Recommended

1. Open the [Homebridge UI](https://github.com/homebridge/homebridge/wiki/Install-Homebridge-on-macOS#complete-login-to-the-homebridge-ui).

2. Open the Plugins tab, search for `homebridge-tiscontrol-wired`, and install the plugin.

3. Log in to TIS through the settings panel, set your TIS Access Token and local IP Com port ipaddress  .

### Manual

1. Install the plugin using NPM:

   ```sh
   npm i -g homebridge-tiscontrol-wired

   ```

## Troubleshooting

If you have any issues with the plugin then you can run homebridge in debug mode, which will provide some additional information. This might be useful for debugging issues.

 If you are facing any issues with any devices.please let us know [here](https://github.com/tiscontrol/homebridge-tiscontrol-wired/issues/new) we will resolve this as soon as possible 

Homebridge debug mode:

 ```sh
   homebridge -D

   ```

## Supports

This project is supported by TIS Contol Limited .
