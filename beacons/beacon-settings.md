---
layout: documentation
title: Beacon Settings
---

Beacon settings determine what your beacons transmit and how they do it.  Beacon settings include Mode, such as iBeacon or Eddystone-UID, and values including Minor or Eddystone-UID.

## Serial #
Beacon serial numbers are unique identifiers for your beacons.  As iBeacon keys or Eddystone-UIDs can change, this should be used to identify a particular beacon if necessary.  Beacon serial numbers are printed or engraved on your beacon:



## Version
The currently reported version of your beacon.  Versions are individual collections of settings.  Whenever beacon settings are changed, a new version is created and automatically set for application on your beacon.

## Pending Updates
When a beacon setting will be changed by a newer version, a pending update field will be displayed with the new setting:



## Mode
The mode defines the type of advertisements that are transmitted by your beacon.  Advertisements are transmissions broadcasted by a BLE device to all devices within range.

- Secure - Non-static rotating identifier.  This is the best option when using the BlueCatsSDKs, have concerns for security, and wish to have offline identifier encryption.
- iBeacon - Static beacon advertising format designed by Apple Inc.
iBeaconPlusSecure - A combination of Secure and iBeacon advertisements.  This is best used when you wish to have a majority of iBeacon advertisements, but also Secure advertisements to confirm the beacon is your beacon.

## Security Type
Security type defines the method of security used to log into the beacon.

None - Beacon authentication not required
Passcode - Use a passcode to secure your beacon
Legacy - Legacy security mode
TwoKey - Two key encryption
TripleKey - AES128 encryption

## Region
The BlueCats platform manages static advertising values through Regions.  A region can define both iBeacon and Eddystone-UID identifiers.  Change regions to change the Proximity UUID and/or Eddystone Namespace ID of your beacons.  For more information on creating a new region, please see this guide.

## iBeacon Settings
Proximity UUID - Proximity UUIDs are used to define a grouping of beacons.  This is typically the same across an entire organization.

Major - Major values can be used to group related beacons that have the same Proximity UUID.  Possible values range from 0 to 65535.

Minor - Minor values distinguish individual beacons with matching Proximity UUIDs and Majors.  Possible values range from 0 to 65535.

Eddystone Settings
Namespace - Namespace IDs are used to define a grouping of beacons.  This is typically the same across an entire organization.

Instance ID - Instance IDs distinguish individual beacons.

Eddystone-UID - The hex representation of the Namespace and Instance IDs to form the complete Eddystone-UID.

Eddystone-URL - If your beacon is in a Mode that includes Eddystone-URL advertisements, this URL will be transmitted from the beacon.

## Target Speed (Advertising Interval)
BlueCats’ beacons have five different behaviors for Target Speed or advertising interval:

Sit: 1,285 ms
Stroll: 760 ms
Walk: 319 ms
Jog: 153 ms
Run: 100 ms
Sprint: 20 ms

## Loudness (Transmission Power)
BlueCats’ Beacons have five different settings for Loudness or transmission power.

Range of Beacon Signal in Free Space (feet)

Model
Loudness	BC202-A	BC303-A	BC403-A
Scream	40	70	70
Shout	20	35	35
Talk	8	14	14
Mutter	5	8	8
Whisper	3	5	5


## Measured Power (Received Signal Strength Indication at One Meter or RSSI)
Measured Power is the value communicating the expected received signal strength indication one meter from the beacon, also called RSSI at one meter.  You can use this value along with the signal strength received by a device to approximate the distance of the device from the beacon, and this is how proximity is proximity is calculated by the BlueCats SDKs.

The default measured power for the respective levels of Loudness are:

Whisper: -89 dBm
Mutter: -85 dBm
Talk: -82 dBm
Shout: -75 dBm
Scream: -63 dBm

## Privacy Duration
BlueCats beacons rotate their Bluetooth MAC Address to enhance the privacy of your network.  This can be set within the Web Manager and applied with BlueCats Reveal.  Please note that low (i.e. a value of 1 minute) privacy duration values can hinder updating beacons from some devices.  When the privacy duration is set to 0, the address does not change.

## Site
Sites group beacons with a common physical location.  Beyond helping organize your network, sites can be used to pre-cache beacon meta-data and trigger geofencing.

## Beacon Name
Beacon name is a simple way to help organize your beacons.  You can use beacon name to help remember beacon location, department, or associated content.

## Categories
Categories are easy tags that can be placed on a beacon.  These tags can represent departments, events, specials, or any context that you with to apply to multiple beacons in a site and across sites.

## Notes
Notes are tidbits you can to add to your beacon.  This can include messages to loved ones and lullabies.

## Model No.
The BlueCats model of your beacon.

## BlueCats models:
AA - BC302-A, BC303-A, and BC313-A
USB - BC202-A
Coin - BC403-A and BC413-A

## Firmware
The current firmware version of your beacon.

## Battery Status
The most recently reported battery percentage of a beacon.

## Custom Values
Key value pairs that can be attached to a beacon.  These can be used to tie specific content to a beacon such as a link to a remote resource or data for a custom event.