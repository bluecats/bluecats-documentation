---
layout: documentation
title: Beacons 101
---

## What is a beacon?
Beacons are devices that use the Bluetooth Low Energy (BLE) protocol to repeatedly send short transmissions, called advertisements, to mobile devices and other. Advertisements can contain identifier and/or sensor data and the brevity of these advertisements allows for battery operated use lasting several years.

## What can I do with beacons? (Why Beacons?)
In their simplest form, beacons can be used to pinpoint your location. At their most complex, beacons can transmit and receive data from sensors and other beacons. Beacons enable (but are not limited to) the following use cases:
 * triggering relevant mobile content for education and shopping experiences
 * initiating data transfer between a mobile device, beacon and point of sale computer to redeem offers
 * logging and reporting temperature data
 * notifying a quick service restaurant of your arrival for order pickup
 * tracking the location of assets in real time

Beacons are essentially broadcasters of data. This data can be static, such as an identifier, public or obfuscated, or data from sensors or devices such as order ID. We have several real world uses in the case study section of our [website](http://bluecats.com/case-study.html).

Choose the right beacon for your project:

- [AA Beacon](https://www.bluecats.com/aa-beacon/) Our most popular beacon. Longest battery life and supports Eddystone, iBeacon and BlueCats advertisement specifications with dust and weather resistant options. AA and Coin Beacon are functionally the same unit. They utilize the BC010 module and have an average range of 100-200 meters. 

- [Coin Beacon](https://www.bluecats.com/coin-beacon/). Compact and powerful. Supports all available Eddystone, iBeacon and BlueCats advertisement specifications with replaceable coin cell battery. AA and Coin Beacon are functionally the same unit. They utilize the BC010 module and have an average range of 100-200 meters. 

- [USB Beacon](https://www.bluecats.com/usb-beacon/). More than a beacon. Scan for beacons nearby and two-way communication between a mobile device and host of BLE via the USB beacon

- [BC010 BLE Module](https://www.bluecats.com/bc010/). The BC010 can be connected directly to a battery or SMT soldered to a host PCB and is ideal for data logging from BlueCats Sensor Boards while the rest of the system is in sleep mode. The module is perfect for application where battery life, small form factor, RF performance and speed to market are important. 
	

### What's BLE, iBeacon, Eddystone?
Bluetooth Low Energy (BLE) is a power friendly version of Bluetooth. Built from the beginning to enable the Internet of Things, BLE is power efficient and extensible to diverse use cases. These goals are achieved by short, customizable transmissions that are sent from BLE enabled devices.

**iBeacon** is a BLE advertisement format defined by Apple that enables iOS applications, open or closed, to be notified when particular beacon ranging events occur. This is most important when you wish to deliver context to a customer even when their application is closed or backgrounded.

**Eddystone** is a collection of open beacon formats created by Google. These formats include the following:
* Eddystone-UID: for sending static beacon identifier information
* Eddystone-URL: for sending a short URL to surrounding devices and can be leveraged by mobile devices using the Chrome app
* Eddystone-TLM: for sending beacon health information to monitor the health of beacons
* Eddystone-EID: for sending encoded beacon identifier information for secure beacon use

### How granular can I be?

Beacons operate as reference points. The more reference points you add, the more granular you can become. Accompanied by the BlueCatsSDKs and BlueCats know-how, applications and devices can define triggers that single out the nearest beacon and trigger the appropriate event. You can even be as granular as defining an interaction to the near tapping of a phone or tablet on a beacon.

### What Makes Bluetooth Low Energy Different from traditional Bluetooth?
Bluetooth Low Energy uses a new framework for device connectivity that is ultra-power efficient and requires no pairing.

In addition, simply having Bluetooth turned on in your phone settings doesn't mean it will drain battery when not paired to your favorite headset or car stereo. When not paired, Bluetooth is passive and scans for connectable devices in a decaying time period. As time passes, the scan for my previously paired devices interval grows to a longer and longer period up to a defined maximum which differs by platform.
