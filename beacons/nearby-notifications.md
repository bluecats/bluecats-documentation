---
layout: documentation
title: Setting Up Nearby Notifications
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


## Setting Up Google Dashboard
Google Dashboard is a management interface that allows you to control your Beacons remotely. 
You can send links or app intents to the Beacon with a custom message. This is allows you to do remote updating.  


### *Setting Up Your Beacons*
After you redeemed your claim code, it is time to set up your Beacon to broadcast in Eddystone UID. 

1. Open the BC Reveal App 
2. Select Your Beacon 
3. Click *continue* and then *Update*
4. Now, Click on mode and select *Eddystone UID*
5. Click *continue* and then *Update*
6. You should be all set 

### *Setting Up Your Phone*
It is important to see if your phone is able to receive Nearby Messages. Each phone is different, so ensuring that your settings are right can save a lot of headaches. 

Nearby messages is a native feature for Android, but not iOS.  

1. Make sure your Bluetooth is on. 
2. Open Settings. 
3. Click on Google.
4. Make sure Nearby Notifications is on. 
5. Then open your notification bar and there should be a setting enabled for *Nearby Messages*.
6. Add Nearby to your home screen for later use. It is not necessary but it is useful for checking Beacons Notifications more quickly. 


### *Setting up the Google Dashboard*

1. Go to the [Google Beacon Dashboard](https://console.cloud.google.com) page and click *Sign in*. 
2. Sign in to your Google account or make one if you do not already have one. You may be prompted for setting up a year Trial. 
3. Once you have signed in, click on the upper left hand corner with the three lines symbol. Go to *API Manager* > *Library* 
4. Then use the search function 'Beacon' to find the 'Beacons API'
5. Click on it and then in the top right click Enable 
6. Click on the arrow or the three hexagons in the top left next to Google Cloud Platform and create and name your Beacon project
7. Once your project has been created sign in here [Beacon Dashboard](https://developers.google.com/beacons/dashboard/)
8. Select your Beacon Project. You should be prompted with a screen that says no Beacons registered. 

### *Registering Your Beacons*
1. Download the "Beacon Tools" for Android or iOS.
2. Select your Beacon Project
3. Click on the Beacons in the Unregistered Tab and register it.
4. You may have to refresh the Beacon Dashboard page 
5. Make sure you click on your Beacon project and select the Beacon you just registered
6. Click *View details* > *Nearby Notifications* 
7. This brings you to the area where you can set your notification as a Web URL or set an App Intent. 
8. Click Web URL 
9. You have to put "en" for English for the ISO 639-1 Code
10. Enter in a Web HTTPS link and a message. 
11. Click save and you should now be able to see a passive notification in the Android Nearby App or in the Android Notifications 



### *Can't See Your Nearby Notifications?*
Eddystone notifications are passive. They will not actively buzz you, and if the device sees the device it will no longer think it is important to show the notification. If you see the Beacon in BC Reveal, but no notification the URL is being broadcasted however the phone thinks it is no longer important. 

On top of that, each phone's Bluetooth hardware is made differently and not all hardware is created equally. A lot of people, are able to see a notification for one second and then it is gone the next. Be aware this protocol is only so reliable and finicky a lot of the times. 




