---
layout: documentation
title: Nearby Notifications 
category: Beacons
---

## Setup Guides

- [Getting Started YouTube Tutorial](https://www.youtube.com/watch?v=brpdd7jon6M)
- Nearby Notifications Guides
	- [Nearby Notifications YouTube Tutorial](https://www.youtube.com/watch?v=Jw14YbDijQM)
	- [Nearby Notifications Written Guide](https://bluecats.github.io/documentation/beacons/guides/nearby-notifications) 
- Eddystone Tutorials
	- [Eddystone URL Setup](https://www.youtube.com/watch?v=MmT3Nhqok0Q)	
	- [Eddystone URL Written Guide](https://bluecats.github.io/documentation/beacons/guides/setting-up-eddystone-url)

## FAQs

<details>
	<summary>How does it work?</summary>

<p> When Nearby detects a broadcasted link to an app or website, it shows you a notification. Unlike most notifications, Nearby notifications:</p>

<ul> - Don't make noise or vibrate </ul>
<ul> - Clear automatically </ul>
<ul> - Show below other notification types </ul>

<p> Nearby Notifications registers each Beacon to Google's Beacon Cloud service. Whenever a phone sees the Beacon, it says hello are you on the cloud and do you have anything for me? If it does, it brings down a notification.</p>

<p> Nearby Notifications allows you to post a URL with a 40 character message on top. It allows you to manage the Beacons far away or remotely once set up. </p>
		
</details>


<details>
	<summary>How much does this cost?</summary>
	
<p> Once you buy the hardware from us (check below on which Beacon to pick). </p>

<p> Nearby Notifications is set up on Google Cloud, which gives you the first year for free or the equivalent of 300 dollars. You do not have to pay a monthly fee for our side of the Beacons. </p>

  
</details>

<details>
	<summary>Which Beacons should I use?</summary>
	
<p>  All of our Beacons' settings like transmission speed and power level are configurable. It should be noted that similar to WiFi, Bluetooth signal can get blocked by cement, metal, water, and even people!  </p>
		
<h2> Coin and AA Beacons </h2>

<p> Our two most popular Beacons are the Coin and the AA Beacons. The Coin Beacons and the AA Beacons are functionally the same units (they have same internal module). They will both get around 100 meters. </p>

<p> The main differences are form factor and battery life. The Coin Beacons will last anywhere between 3 months, while the AA Beacons will last around 2 years. If you are going to leave the Beacons in one spot, I definitely recommend the AA Beacon for less maintenance. </p>

<h2> USB Beacon </h2>

<p> Our USB Beacon is a great alternative if you have a power source. The Beacon has a distance of 20-40 meters. </p>


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
  
</details>


<details>
	<summary>Will this work with iOS or iPhones?</summary>

<p> No, unfortunately this will only work with Android Devices. All phones need a mobile application to interpret the Beacon's signal.  Unfortunately, Nearby Notification or Eddystone URL notifications only work the pre-installed Android's Nearby App. </p>

<p> The phones don't care if it is iBeacon or Eddystone UID. They just need a way to interpret the signal, and Nearby Notifications or building a mobile application is a way to interpret that signal. </p>

  
</details>
	
<details>
	<summary>Eddystone URL VS. Nearby Notifications </summary>
	
<p> Eddystone URL is programming a URL directly to the Beacon. It can only be changed when you are in Bluetooth range of the device with your phone. </p>

<p> Nearby Notifications registers each Beacon to Google's Beacon Cloud service. Whenever a phone sees the Beacon, it says hello are you on the cloud and do you have anything for me? If it does, it brings down a notification. </p>
  
</details>


## Troubleshooting 

<details>
	<summary> Why is my notification not working or showing up? </summary>
		
<p> There a few reasons why your notification could be not showing up: </p> 

<ol> 1. A notification won't show if the attachment is not well received by users. </ol>
<ol> 2. Make sure your Beacon has battery. Try replacing the batteries and checking if the Beacons show up in BC Reveal. </ol>
<ol> 3. The URL is not secure or being verified by Google. Make sure that you ensure your URL is being verified by the <a href="https://beaufortfrancois.github.io/sandbox/physical-web/url-validator/" title="URL Validator"> URL Validator </a> . Ensure that you have set up everything else right as well. </ol>
<ol> 4. The Notification has already been seen or if the notification has been dismissed on a device recently, that device may not show another notification a period of time. The backoff policy is also reset if the user opens the Nearby section of Google Settings. </ol>
<ol> 5. Your phone could be older or does not have at least KitKat or Bluetooth and Data. </ol>
<ol> 6. Nearby Notifications typically scans for beacons for a few seconds after the screen is turned on. If the screen has not been turned on for a while, the device won't discover new beacons.</ol>


<p> A notification may not show if it violates the Nearby Notifications <a href="https://developers.google.com/nearby/notifications/policies" title="policies">policies</a>. Make sure that your notfication is NOT violating Google's policies </p>


</details>

<details>
	<summary>Why don't I see any metrics?</summary>
	
<p> Unless you build a mobile application with our SDK, you will not see any metrics on the BlueCats web app. It is built to only receive data from developers who created mobile applications. </p>
		
<p> Google Cloud does not have any data reporting. It will tell you if there is high or low activity. However if you want more data, you can set the unique links to Google Analytics or another web analytic tool to find how often the link is visited. </p>
  
</details>


<details>
	<summary>Issues registering with Nearby? </summary>
		
<p>  There a few reasons you may have registering issues.  </p>

<ol> 1. Google no longer has Beacon Tools for iOS. It is only for Android devices. </ol>
<ol> 2. We have found a bug in Beacon Tools, that says "This Beacon does not support hardware configuration". However, by adding a description we can get around this. The YoutTube tutorial goes over this bug <a href="https://youtu.be/Jw14YbDijQM?t=9m28s" title="Nearby Troubleshooting"> here </a>  </ol>
<ol> 3. Another Bug is once you add a description, the Beacon does get registered. </ol>
We have found that even though you registered your Beacon it will not show up in "Registered Tab". However, it will show up under the "All My Beacons" tab.
<ol> 4. For Beacons not showing up in Beacon Tools, make sure your Bluetooth is on, the Beacons are in Eddystone UID mode, and for extra troublesome beacons, give them new batteries. </ol>  



<p> After that, you can go ahead and update the notification through the <a href="https://developers.google.com/beacons/dashboard/" title="Google Beacon Dashboard"> Google Beacon Dashboard </a> </p>

</details>



<details>
	<summary>How do I get my signal to go farther?</summary>
	
<p> All of our Beacons' settings like transmission speed and power level are configurable. It should be noted that similar to WiFi, Bluetooth signal can get blocked by cement, metal, water, and even people! </p>

<p>  So be noted if you put it in buildings or cars or the like. </p>

</details>


<details>
	<summary>Having issues with Google Beacon Dashboard?</summary>

<p> There are two reasons for seeing this screen when you pull up the <a href="https://developers.google.com/beacons/dashboard/" title="Google Beacon Dashboard"> Google Beacon Dashboard </a></p> 

<ol> 1. You need to register your Beacons still OR </ol>
<ol> 2. What you need to do is go to the dashboard and click this arrow three times. Then you should see your Beacons. See the screenshot below. </ol>


<p> <img src="https://s3-us-west-1.amazonaws.com/github-photos/DeveloperDocs/Beacons/beaconDashboardStuck.png" title="Dashboard Stuck"> </p>

</details>


### For more information visit:

- [Nearby Notifications FAQ](https://support.google.com/accounts/answer/6260286?hl=en)
- [Developer's FAQ](https://developers.google.com/nearby/notifications/developer_faq)
- [Getting Started with Nearby API](https://developers.google.com/nearby/messages/android/get-started)