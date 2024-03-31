
# Wifi Jammer with ESP2866


A WiFi deauther is a type of tool or device used to perform deauthentication attacks on WiFi networks. These attacks involve sending deauthentication frames to one or more devices connected to a WiFi network, causing them to disconnect or lose their connection to the network temporarily.


## Table of Contents

- [Jammer X Deauther](#jammer)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgements](#acknowledgements)

## Jammer X Deauther

A Wi-Fi deauther is a device that sends deauthentication packets to disconnect specific devices from a Wi-Fi network, often used for network security testing or troubleshooting. It targets individual devices and is generally considered less intrusive and more legally permissible compared to a Wi-Fi jammer.

A Wi-Fi jammer, on the other hand, disrupts entire Wi-Fi signals within its range by flooding the Wi-Fi spectrum with interference. It affects all devices within its vicinity and is typically illegal due to its indiscriminate disruption of Wi-Fi networks.

## Installation

1. First you need to have the "nodemcu-flasher" installed in your pc.

2. After the installation open the "nodemcu-flasher", it should look like this:

3. Go to "Config" select your ESP2866 and click on  the "gear", select the bin file.

4. Go to "Operation" select the COM Port where the ESP2866 is connect and click on "flash".

## Usage

1. Open your Wifi and should appear a host called "Pnwed", the password is "deauther".

2. After connecting to the host open your broswer and tpye the IP.

3. Now you have acess to the Deauther.

## Modes of Attack

1. Deauther mode:
 
Attacks the select Wifi sending deauthentication packets. 

2. Beacon mode:

Creates Wifi host.

3. Probe-request mode:

Tets the select Wifi.

## Link you may need

nodemcu-flasher: <https://github.com/nodemcu/nodemcu-flasher>.
