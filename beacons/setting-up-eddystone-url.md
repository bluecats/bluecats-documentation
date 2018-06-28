---
layout: documentation
title: Setting Up Eddystone URL
---

Eddystone is the Google's Beacon Protocol. Eddystone has multiple 
Eddystone UID gives each Beacon a unique identifier, which allows for remote control of the Beacons content. 

After you have used your claim code to claim your Beacons in the [BlueCats Web App](https://app.bluecats.com/), download the BC Reveal app, which is our management app on [Android](https://play.google.com/store/apps/details?id=com.bluecats.bcreveal&hl=en) or [iOS](https://itunes.apple.com/us/app/bc-reveal/id852676494?mt=8). See if your Beacons are showing up in the BC Reveal app. 

*Troubleshooting if you can't see your Beacon:*      

* Go to your BC Reveal App. There are Tabs at the bottom. Sometimes there is a caching issue. 
	1. Click on the Tab *Teams*. 
	2. Go to your Team. Click on *Beacons*. Pull down on the page to refresh. 
	3. And you should be able to find the Beacon there. 
	4. This will then put it in the sniffer side.

* Try closing out the BC Reveal App completely. Sometimes there is an issue with caching. 
* Pull the batteries out again. It never hurts. 

## Setting Up Eddystone URL
Eddystone URL broadcasts exclusively a URL. This sends a passive notification to a phone or gateway device. 

### *Making your URL Eddystone compatible*

Google wants to ensure that the URL are sending is secure. In order to broadcast your URL, it must be an HTTPS certified link. Secondly, Google requires your URL link to be 17 characters or less. If your link is longer, you should run it through a URL shortener like [goo.gl](https://goo.gl/) or [Tiny Url](https://tinyurl.com/). 

Once you have your URL, you should verify it with [Google's URL Validator](https://beaufortfrancois.github.io/sandbox/physical-web/url-validator/). 

### *Setting Up Your Beacons*
After you set up your URL, it is time to set up your Beacon to broadcast your URL. 

1. Open the BC Reveal App 
2. Select Your Beacon 
3. Now you should add your URL to the Eddystone URL text box
4. Click *continue* and then *Update*
3. Now, Click on mode and select *Eddystone URL*
4. Click *continue* and then *Update*
5. You should be all set 

### *Setting Up Your Phone*
It is important to see if your phone is able to receive Eddystone URL notifications. Each phone is different, so ensuring that your settings are right can save a lot of headaches. 

For Android: 

1. Make sure your Bluetooth is on. 
2. Open the Chrome App. 
3. Open Settings. 
4. Click on Privacy.
5. Make sure Physical Web is on. 
6. Then open your notification bar and there should be a notification for 'Physical Web'.

For iOS:
  
1. Make sure your Bluetooth is on. 
2. Scroll to your left to the Widgets page. Then Click Edit at the bottom of the page. 
3. Click on the green plus arrow and add Chrome. 
4. Click done and go back to your Widgets.
5. You should see the Beacon URL add in the Chrome widget.

### *Can't See Your Eddystone URL Notification?*
Eddystone URL notifications are passive. They will not actively buzz you, and if the device sees the device it will no longer think it is important to show the notification. If you see the Beacon in BC Reveal, but no notification the URL is being broadcasted however the phone thinks it is no longer important. 

On top of that, each phone's Bluetooth hardware is made differently and not all hardware is created equally. A lot of people, are able to see a notification for one second and then it is gone the next. Be aware this protocol is only so reliable and finicky a lot of the times. 