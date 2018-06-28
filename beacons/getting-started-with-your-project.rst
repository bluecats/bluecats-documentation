Beacons are devices that use the Bluetooth Low Energy (BLE) protocol to
repeatedly send short transmissions, called advertisements, to mobile
devices or other Bluetooth scanning device. Advertisements can contain
an identifier and/or sensor data and the brevity of these advertisements
allows for battery operated use lasting several years.

In their simplest form, beacons can be used to pinpoint your location.
At their most complex, beacons can transmit and receive data from
sensors and other beacons. Beacons enable (but are not limited to) the
following use cases:

-  triggering relevant mobile content for education and shopping
   experiences
-  initiating data transfer between a mobile device and usb or OEM
   beacon at point of sale computer to redeem offers
-  logging and reporting temperature data
-  notifying a quick service restaurant of your arrival for order pickup
-  tracking the location of assets in real time
-  Beacons are essentially broadcasters of data. This data can be
   static, such as an identifier, public or obfuscated, or data from
   sensors.

Getting Started With Your Project
=================================

Ready to go with your beacon project? Start here for everything you need
to get up and running:

1. Choose the right beacon for your project

   -  `AA Beacon <https://www.bluecats.com/aa-bluetooth-beacon/>`__ Our
      most popular beacon. Longest battery life and full Eddystone EID
      support with dust and weather resistant options.
   -  `USB Beacon <https://www.bluecats.com/usb-beacon/>`__. More than a
      beacon. Scan for beacons nearby and two-way communication between
      a mobile device and host of BLE via the USB beacon
   -  `Coin Beacon <https://www.bluecats.com/coin-mobile-beacon/>`__.
      Compact and powerful. Supports all available Eddystone, iBeacon
      and BlueCats advertisement specifications with replaceable coin
      cell battery.
   -  `BC010 BLE Module <https://www.bluecats.com/bc010-ibeacon/>`__.
      The BC010 can be connected directly to a battery or SMT soldered
      to a host PCB and is ideal for data logging from BlueCats Sensor
      Boards while the rest of the system is in sleep mode. The module
      is perfect for application where battery life, small form factor,
      RF performance and speed to market are important.

2. Create a BlueCats account and claim your beacons with the the
   `BlueCats Web App <https://app.bluecats.com/>`__, download the BC
   Reveal app, which is our management app on
   `Android <https://play.google.com/store/apps/details?id=com.bluecats.bcreveal&hl=en>`__
   or
   `iOS <https://itunes.apple.com/us/app/bc-reveal/id852676494?mt=8>`__
3. Choose an advertisement format and configure your beacons with the BC
   Reveal app
4. Every beacon project is different. Choose your beacon configuration
   and tools and start building: Install the BlueCats SDK or iOS or
   Android into your mobile app to enable cross-platform proximity
   detection and analytics Use your beacons with any iBeacon compatible
   application or library No app? Eddystone-URL and the Physical Web

Supported Beacon Specifications
===============================

BlueCats beacon hardware and Platform provide complete flexibility to
choose a beacon format best suited to your application. With BlueCats
beacons you can support any of the following open or BlueCats
proprietary specifications:

-  `iBeacon <https://developer.apple.com/ibeacon/>`__ – Apple’s release
   of the iBeacon BLE specification and deep native support in 2014
   brought beacon technology to the main stream. Still the best choice
   for many consumer mobile app use cases where support for both iOS and
   Android devices is required.
-  `Eddystone <https://developers.google.com/beacons/eddystone>`__ –
   Eddystone is an open beacon format developed by Google and designed
   with transparency and robustness in mind. Eddystone can be detected
   by both Android and iOS.

   -  Eddystone-UID,
   -  Eddytone-URL (or Physical Web)

-  BlueCats Platform - need to do something not supported by the open
   beacon protocols? BlueCats have a range of advertisements and BLE
   libraries to fill the gaps and extend the capabilities of a Bluetooth
   beacon network.

   -  BlueCats Secure
   -  Sensor
   -  Data Transfer

Edge Relay
==========

The Edge Relay is a customisable gateway that allows you to scan for BLE
(Bluetooth Low Energy) traffic and send that data to different
endpoints. Capture all of your Bluetooth devices in range using the
popular formats: iBeacon, Eddystone, and our custom beacons. Control the
flow of your data using signal smoothing, filtering, and throttling to
get exactly the data you need. Once you have your data, you can
communicate it to your endpoints using UDP or MQTT protocols.
