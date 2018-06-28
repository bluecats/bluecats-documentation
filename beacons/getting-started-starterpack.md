---
layout: documentation
title: Getting Started with the StarterPack
---

#### Welcome to BlueCats!
This guide will show you how to get your new kittens purring.

<!--
<div style="text-align:center">
<img src="https://s3-us-west-1.amazonaws.com/sdk-guide/gelato/flatpack_1024x1024.jpg">
</div>
-->

##### Installing Batteries in AA Beacons
1) The mounting plate is removed by depressing the tab on the top of the mounting plate and 2) turning the plate counter-clockwise.  
<div style="text-align:center"><img src="https://s3-us-west-1.amazonaws.com/sdk-guide/gelato/soloStep1.png"></div>

3) The battery bay can be accessed by removing the two Phillips-head screws on the back of the beacon and 4) removing the mounting plate.  
![](https://s3-us-west-1.amazonaws.com/sdk-guide/gelato/soloStep2.png)  
5) Insert the positive side of the battery into the beacon first.  There are small imprints within each section of the battery bay to indicate the correct battery orientation.
![](https://s3-us-west-1.amazonaws.com/sdk-guide/gelato/batteryOrientation.png)

*Note*: If you are unsure if you have put the mounting plate on correctly remember that the plate locks into place with a click by turning clockwise. The mounting plate will be flat against your mounting surface except for the small indentation for double sided sticky tape.

##### Powering USB Beacons
To feed your USB beacon, simply plug it into any standard USB port! This includes USB wall adapters or battery powered phone chargers with USB ports.

##### What are my beacons doing now?
Your beacons have been pre-configured and once powered, your beacons will begin advertising in iBeacon mode - no setup required. To find the iBeacon keys for your beacons or change their values or mode, create a management account. The default Proximity UUID of BlueCats beacons is: 61687109-905F-4436-91F8-E602F514C96D.

##### Create Your Management Account
![](https://s3-us-west-1.amazonaws.com/sdk-guide/gelato/spSignup.png)
Enter the StarterPack Code contained in your StarterPack into app.bluecats.com/join/starterpack to establish your management account. This step will create your first team and site to which all of your beacons will be initially placed. For more information on the BlueCats hierarchy, please see this article.

##### Logging into the Web App and Viewing Your Beacons
Log into the BlueCats' web app via app.bluecats.com with your email or BlueCats username. A guide to the web app is available here.

Information regarding your beacons is located in the Beacons section of the web app. Here you can create new versions for your beacons or view their battery life.
![](https://s3-us-west-1.amazonaws.com/sdk-guide/gelato/beaconCell-1-13-16.png)

##### How does the web app talk to my beacons?
BlueCats beacons do not send battery life or visit information directly to the web app. This is collected and posted to the BlueCats Platform by the BlueCatsSDKs and then is visible in the web app. Apps such as BlueCats Tour contain the BlueCatsSDK and will collect this information. BlueCats Reveal does not collect this information or generate visits.

##### BlueCats Software Development Kits (SDKs)
The BlueCatsSDKs are located on github:
Android SDK - SDK Documentation
iOS SDK - SDK Documentation

##### Beacon Management
Available for [iOS](https://itunes.apple.com/us/app/bc-reveal/id852676494?mt=8) and [Android](https://play.google.com/store/apps/details?id=com.bluecats.bcreveal), BlueCats Reveal is the BlueCats beacon management app. BlueCats Reveal has most of the functionality of the web app with the ability to connect directly to BlueCats beacons to update their settings or firmware.

Guides to using BlueCats Reveal can be found [here](http://support.bluecats.com/customer/en/portal/topics/667683-bluecats-reveal/articles).

##### Demo Apps
[BlueCats LitterBox](https://itunes.apple.com/us/app/bc-litterbox/id807946568?mt=8) (iOS) is a demo app using Sites, Categories, and Proximities. A guide to using BC LitterBox is available [here](http://support.bluecats.com/customer/en/portal/articles/1495603-playing-with-bluecats-litterbox-ios-).

BlueCats Tour ([iOS](https://itunes.apple.com/us/app/bluecats-tour/id912105747?mt=8) and [Android](https://play.google.com/store/apps/details?id=com.bluecats.bctour&hl=en)) works with the default categories on your StarterPack beacons. BlueCats tour demonstrates different ways you can use beacons to interact with users by altering the view or rendering their location on a floor plan or map. A guide to using BlueCats Tour is available [here](http://support.bluecats.com/customer/en/portal/articles/2038418-taking-a-bluecats-tour).

##### Sample Code!
Check out the BlueCats Github [page](https://github.com/bluecats) for iOS and Android sample code.
