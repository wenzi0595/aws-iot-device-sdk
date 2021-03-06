# Arrow DragonBoard 410c

Arrow's DragonBoard&trade; 410c AWS IoT starter kit has the following contents:
* [Arrow DragonBoard&trade; 410c development board](http://partners.arrow.com/campaigns-na/qualcomm/dragonboard-410c/awsiotstarterkit/)
* Power Supply 12V 2A
* DragonConnect - Demo App written in C
* DragonPulse - Demo app written in NodeJS

![Image of Board Callout](https://raw.githubusercontent.com/ArrowElectronics/aws-iot-device-sdk/master/images/dragonboard_callouts.png)

Smaller than a standard playing card, the DragonBoard&trade; 410c packs a lot
in a tiny footprint, including a quad-core 1.2Ghz Snapdragon 410 processor,
1GB RAM, 8GB SanDisk e.MMC storage, on-board WLAN, GPS, and Bluetooth.

![Image of IoT Stack](https://raw.githubusercontent.com/ArrowElectronics/aws-iot-device-sdk/master/images/iot_infographic.png)

The Starter Kit ecosystem can be setup in a matter of minutes by using a
standard monitor and keyboard, connecting to the internet with the
Dragonboard&trade;, and running the demos.

Combining the unique features of DragonBoard&trade; with Amazon Web Services
creates an integrated ecosystem for bringing any project online.

# Getting Started

### Requirements
* Standard monitor
* HDMI cable to connect DragonBoard&trade; to monitor (HDMI->DVI or HDMI->HDMI)
* USB Keyboard
* USB Mouse
* Wi-Fi internet connection

## Configuring the Starter Kit

Please perform the following steps:
* Connect the DragonBoard&trade; to the external monitor via HDMI connector
* Connect USB Keyboard and mouse

### Login to the DragonBoard&trade;

**username** linaro

**password** linaro

### Setup Internet Connection

* In the bottom right of the deskop, left-click the network icon

![Image of Network Icon](https://raw.githubusercontent.com/ArrowElectronics/aws-iot-device-sdk/master/images/network_icon.png)

* Choose the appropriate network, enter password as necessary

![Image of Network Menu](https://raw.githubusercontent.com/ArrowElectronics/aws-iot-device-sdk/master/images/network_menu.png)

### Install demo-prerequisites

* In the bottom left of the desktop, left-click the start-like icon

![Image of Start Icon](https://raw.githubusercontent.com/ArrowElectronics/aws-iot-device-sdk/master/images/start_icon.png)

* Navigate to System Tools > LXTerminal

![Image of Start Icon](https://raw.githubusercontent.com/ArrowElectronics/aws-iot-device-sdk/master/images/terminal.png)


### DragonConnect

Connects and communicates with the DragonBoard&trade;. Written in C and
integrating a 2-way MQTT channel through Amazon AWS, DragonConnect
reads/writes to Ubuntu file handlers allowing control of on-board IO.

The <a href="https://github.com/ArrowElectronics/aws-iot-dragonconnect-c" target="_blank">quick getting started guide</a> and source code for the project is available at <a href="https://github.com/ArrowElectronics/aws-iot-dragonconnect-c" target="_blank">GitHub</a>.

If you'd like more detailed documentation about the steps involved in configuring and deploying the DragonConnect project, it is also available at the <a href="https://arrowelectronics.github.io/aws-iot-dragonconnect-c/" target="_blank">DragonConnect Project Pages</a> on GitHub.

### DragonPulse

Utilizes NodeJS, MQTT protocol, and Amazon AWS services, to interact with
Ubuntu shell commands. Extract performance and summary statistics to
remotely monitor top CPU consumption, memory usage, network traffic,
and disk space.

The <a href="https://github.com/ArrowElectronics/aws-iot-dragonpulse-js/" target="_blank">quick getting started guide</a> and source code for the project is available at <a href="https://github.com/ArrowElectronics/aws-iot-dragonpulse-js/" target="_blank">GitHub</a>.

If you'd like more detailed documentation about the steps involved in configuring and deploying the DragonPulse project, it is also available at the <a href="https://arrowelectronics.github.io/aws-iot-dragonpulse-js/" target="_blank">DragonPulse Project Pages</a> on GitHub.


# License
This SDK is distributed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0),
see LICENSE.txt and NOTICE.txt for more information.
