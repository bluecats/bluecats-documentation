---
layout: documentation
title: Guides
category: Beacons
---


In their simplest form, beacons can be used to pinpoint your location. At their most complex, beacons can transmit and receive data from sensors and other beacons. Beacons enable (but are not limited to) the following use cases:

- triggering relevant mobile content for education and shopping experiences
- initiating data transfer between a mobile device and usb or OEM beacon at point of sale computer to redeem offers
- logging and reporting temperature data
- notifying a quick service restaurant of your arrival for order pickup
- tracking the location of assets in real time


## Getting Started 

Beacons are essentially broadcasters of data. This data can be static, such as an identifier, public or obfuscated, or data from sensors.

>> [Getting Started With Your Beacon Project]({{ '/documentation/beacons/guides/getting-started-with-your-project' | relative_url }})

>> [Getting Started YouTube Tutorial](https://www.youtube.com/watch?v=brpdd7jon6M)

>> [Troubleshooting Your Beacons](https://www.youtube.com/watch?v=DFujBQNz4r4)


## Understanding Beacons 

Beacons are devices that use the Bluetooth Low Energy (BLE) protocol to repeatedly send short transmissions, called advertisements, to mobile devices and other. Advertisements can contain identifier and/or sensor data and the brevity of these advertisements allows for battery operated use lasting several years.

>> [Beacons 101]({{ '/documentation/beacons/guides/beacons101' | relative_url }})

>> [Different Beacon Settings]({{ '/documentation/beacons/guides/beacon-settings' | relative_url }})

>> [What Target Speed or Loudness?]({{ '/documentation/beacons/guides/what-target-speed-loudness' | relative_url }})

## Advertising with Beacons

Proximity marketing allows you to send soft notfications to Android devices so that you can advertise to people. For more information check out our Advertising with Beacons guide below: 

>> [Advertising with Beacons Guide]({{ '/documentation/beacons/guides/nearby-notifications-faq' | relative_url }}) 




## FAQs

<details>
	<summary>What is a Beacon?</summary>

<p>Beacons are devices that use the Bluetooth Low Energy (BLE) protocol to repeatedly send short transmissions, called advertisements, to mobile devices and other. Advertisements can contain identifier and/or sensor data and the brevity of these advertisements allows for battery operated use lasting several years. </p>

<p>Broadly, you can use Beacons for two main things: </p>

<ol> 1. Asset and People tracking </ol>
<ol> 2. Marketing or Retail </ol>

		
</details>




<details>
	<summary>What can I do with Beacons? </summary>

<p> In their simplest form, beacons can be used to pinpoint your location. At their most complex, beacons can transmit and receive data from sensors and other beacons. Beacons enable (but are not limited to) the following use cases: </p>

<ul> - triggering relevant mobile content for education and shopping experiences </ul>
<ul> - initiating data transfer between a mobile device, beacon and point of sale computer to redeem offers </ul>
<ul> - logging and reporting temperature data </ul>
<ul> - notifying a quick service restaurant of your arrival for order pickup </ul>
<ul> - tracking the location of assets in real time </ul>

<p> Beacons are essentially broadcasters of data. This data can be static, such as an identifier, public or obfuscated, or data from sensors or devices such as order ID. </p>

</details>




<details>
	<summary >Which Beacons should I use?</summary>
	
<p> All of our Beacons' settings like transmission speed and power level are configurable. It should be noted that similar to WiFi, Bluetooth signal can get blocked by cement, metal, water, and even people!   </p>
		
<h3> Coin and AA Beacons </h3>

<p> Our two most popular Beacons are the Coin and the AA Beacons. The Coin Beacons and the AA Beacons are functionally the same units (they have same internal module). They will both get around 100 meters. </p>

The main differences are form factor and battery life. The Coin Beacons will last anywhere between 3 months, while the AA Beacons will last around 2 years. If you are going to leave the Beacons in one spot, I definitely recommend the AA Beacon for less maintenance. 

<h3> USB Beacon </h3>

Our USB Beacon is a great alternative if you have a power source. The Beacon has a distance of 20-40 meters. 


<p> Here are the details on volume pricing for our USB Beacons, AA Beacons, and Coin Beacons: </p>

<table style="width:100%">
  <tr>
    <th>Beacons</th>
    <th>0-100</th> 
    <th>101-500</th>
    <th>501-1000</th>
  </tr>
  <tr>
    <td>AA Beacon (313)</td>
    <td>$30.00</td> 
    <td>$28.10</td>
    <td>$26.23</td>

  </tr>
  <tr>
    <td>Coin Beacon (413)</td>
    <td>$15.00</td> 
    <td>$14.02</td>
    <td>$13.05</td>
  </tr>
  <tr>
    <td>USB Beacon (202)</td>
    <td>$25.00</td> 
    <td>$23.16</td>
    <td>$21.75</td>
  </tr>
</table>


<p> Technical Specification Sheets: </p>

<ul> <a href="https://dpzktgqza6wo8.cloudfront.net/wp-content/uploads/2017/02/BCT001-PC-SpecSheet-USB-v21_AA-313-Beacon.pdf" title="AA Beacon Spec Sheet">AA Beacon Spec Sheet</a> </ul> 

<ul> <a href="https://dpzktgqza6wo8.cloudfront.net/wp-content/uploads/2016/11/BCT001-PC-SpecSheet-USB-v21_Coin-Beacon.pdf" title="Coin Beacon Spec Sheet">Coin Beacon Spec Sheet</a> </ul> 

<ul> <a href="https://dpzktgqza6wo8.cloudfront.net/wp-content/uploads/2016/11/BCT001-PC-SpecSheet-USB-v21_USB-Beacon.pdf" title="USB Beacon Spec Sheet">USB Beacon Spec Sheet </a> </ul> 

<ul> <a href="https://www.bluecats.com/bc010-ibeacon/" title="UBC010 Module Module Spec Sheet">BC010 Module Module Spec Sheet </a> </ul> 

  
</details>



	
<details>
	<summary> How do I advertise with Beacons?</summary>
	
<p> What you are going to want to use is either Eddystone URL or Nearby notifications. </p>

<p> For more information visit our:  <a href="https://bluecats.github.io/documentation/beacons/guides/nearby-notifications-faq" title="Advertising with Beacons Guide">Advertising with Beacons Guide </a> </p>
  
</details>




<details>
	<summary> What is the Edge Relay? </summary>

<p> The BlueCats Edge Relay is a powerful device that is a Bluetooth Scanner that can send raw, filtered, or intelligently processed BLE scan data and events to whatever MQTT, HTTP, and UDP endpoint that you desire. </p>

<p>You can supply power to the Edge Relay via Power over Ethernet (PoE) or micro-USB.  It can attach to Local Networks and the Internet via dual Ethernet ports or as a WiFi Client, and can additionally act as a WiFi Access Point </p>

<p> For more information and getting started visit here: </p>

<p> <a href="https://bluecats.github.io/documentation/edge/edge-0.2.X-0.4.X/getting-started-connect#connecting-to-the-edge" title="Edge Relay Guide">Edge Relay Guide </a> </p>


  
</details>



## Troubleshooting 

<details>
	<summary>Can't Update Beacon Settings or Firmware? </summary>

<p> Some reasons of why the Beacon cannot be connected  could be a range, phone, or battery issue. For these troublesome Beacons we are going to want to get the firmware updated: </p>
<p> - Open the Beacon up and remove the battery </p>
<p> - Put the Battery back in </p>
<p> - Open up BC Reveal  </p>
<p> - There are two ways to click on Beacon: </p>
<ol> 1) Pull down on Sniffer screen to refresh Beacons. </ol>
<ol> 2) Click on the Beacon and then scroll to the Bottom. </ol>
<ol>  	Go to Teams > Beacons > Click on that Beacon </ol>
<p> - Click Update firmware </p>

<p> You may have to try this a few times to get it right. </p>
	
<h3> Troubleshooting Guides: </h3>

<ul> <a href="https://www.youtube.com/watch?v=HbVKt4kEgyA" title="Updating Your Beacon's Settings">Updating Your Beacon's Settings</a></ul>
<ul> <a href="https://www.youtube.com/watch?v=DFujBQNz4r4" title="Troubleshooting Your Beacons">Troubleshooting Your Beacons</a></ul>
<ul> <a href="https://www.youtube.com/watch?v=hGc1VeQRzpc" title="Coin Cell Battery Removal Video">Coin Cell Battery Removal Video</a></ul>
 
</details>



<details>
	<summary>Why don't I see any metrics in the BlueCats dashboard?</summary>
	
<p> Unless you build a mobile application with our SDK, you will not see any metrics on the BlueCats web app. It is built to only receive data from developers who created mobile applications. </p>
		
<p> Google Cloud does not have any data reporting. It will tell you if there is high or low activity. However if you want more data, you can set the unique links to Google Analytics or another web analytic tool to find how often the link is visited. </p>
  
</details>




<details>
	<summary>Trouble connecting to a beacon? Peripheral is Null?</summary>

<p> If you are having issues connecting, or if you receive a message Peripheral is Null means the phone is not contacting the Beacon. 
If your Beacon is in older firmware, you will want to update it to the newest firmware. </p>

<p> A couple things to try: </p>

<ol> 1. Try shutting down the app completely. </ol>
<ol> 2. Try shutting off Bluetooth. </ol>
<ol> 3. Try removing the battery and then updating the beacon once you put the battery back in. </ol>


</details>




<details>
	<summary>How do I get my signal to go farther?</summary>
	
<p> All of our Beacons' settings like transmission speed and power level are configurable. It should be noted that similar to WiFi, Bluetooth signal can get blocked by cement, metal, water, and even people! </p>

<p> So be noted if you put it in buildings or cars or the like. </p>

</details>




<details>
	<summary>Battery Life?</summary>

<p> For AA Beacons, they do not come with batteries. Make sure you get fresh batteries in there. 
Sometimes the Coin Beacons tab does not prevent the battery from making contact, and therefore drains the batteries. Also, batteries are imperfect and discharge at a non-linear rate! </p>

<p> If you are seeing low battery, check the battery life expectancy and replace if it is low. </p>


<b>Important:</b> The power level will only affect about 20% of the battery life. The advertisement speed is what drains the battery the most!


<h3> Battery Life Expectancy </h3>

<p> Below are the battery life expectancies for AA Beacons and the Coin Beacons, based on the settings for transmission power and advertisement speed. </p>


<h3> AA Beacon: Battery Life </h3>


<table style="width:100%">
  <tr>
    <th></th>
    <th>Whisper (-21 dbm)</th> 
    <th>Mutter (-15 dbm)</th>
    <th>Talk (-9 dbm)</th>
    <th>Shout (0-1 dbm)</th>
    <th>Scream (5 dbm)</th>
  </tr>
  <tr>
    <td>Sit (1285 ms)</td>
    <td>90 months </td> 
    <td>91 months </td>
    <td>89 months </td>
    <td>86 months</td>
    <td>77 months </td>

  </tr>
  <tr>
    <td>Stroll (760 ms)</td>
    <td>58 months</td> 
    <td>57 months </td>
    <td>56 months </td>
    <td>52 months</td>
    <td>49 months </td>
  </tr>
  <tr>
    <td>Walk (319 ms)</td>
    <td>26 months</td> 
    <td>25.5 months </td>
    <td>25 months </td>
    <td>22 months</td>
    <td>21 months </td>
  </tr>
  <tr>
    <td>Jog (153 ms)</td>
    <td>13 months</td> 
    <td>12.5 months </td>
    <td>12 months </td>
    <td>11.5 months</td>
    <td>11 months </td>
  </tr>
  <tr>
    <td>Run (100 ms)</td>
    <td>9 months</td> 
    <td>8.5 months </td>
    <td>8 months </td>
    <td>7.8 months</td>
    <td>7 months </td>
  </tr>
</table>

 

<h3> Coin Beacon: Battery Life </h3>

<table style="width:100%">
  <tr>
    <th></th>
    <th>Whisper (-21 dbm)</th> 
    <th>Mutter (-15 dbm)</th>
    <th>Talk (-9 dbm)</th>
    <th>Shout (0-1 dbm)</th>
    <th>Scream (5 dbm)</th>
  </tr>
  <tr>
    <td>Sit (1285 ms)</td>
    <td>12.2 months </td> 
    <td>12 months </td>
    <td>11.9 months </td>
    <td>11.5 months</td>
    <td>10.3 months </td>

  </tr>
  <tr>
    <td>Stroll (760 ms)</td>
    <td>7.8 months</td> 
    <td>7.6 months </td>
    <td>7.5 months </td>
    <td>6.9 months</td>
    <td>6.6 months </td>
  </tr>
  <tr>
    <td>Walk (319 ms)</td>
    <td>3.4 months</td> 
    <td>3.3 months </td>
    <td>3.2 months </td>
    <td>3.0 months</td>
    <td>2.8 months </td>
  </tr>
  <tr>
    <td>Jog (153 ms)</td>
    <td>1.7 months</td> 
    <td>1.6 months </td>
    <td>1.5 months </td>
    <td>1.5 months</td>
    <td>1.4 months </td>
  </tr>
  <tr>
    <td>Run (100 ms)</td>
    <td>1.3 months</td> 
    <td>1.2 months </td>
    <td>1.1 months </td>
    <td>1.0 months</td>
    <td>0.9 months </td>
  </tr>
</table>

</details>







