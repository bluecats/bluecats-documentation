BlueCats Beacons ship with two main communication settings: *Target
Speed* and *Loudness*. Determining the correct Beacon configuration, is
key to getting the most battery life and performance out of your Beacon.

**Target Speed**: The target speed is the advertising interval. This is
how often frequency of which your Beacon is sending your advertisements.

| Sit: 1,285 ms
| Stroll: 760 ms
| Walk: 319 ms
| Jog: 153 ms
| Run: 100 ms

+----------------+---------------+
| Walking        | Jog           |
+================+===============+
| |Walk-Diagram| | |Jog-Diagram| |
+----------------+---------------+

**Loudness**: Loudness is the strength or intensity of which the
advertisements are broadcasted.

| Whisper: -21 dBm
| Mutter: -15 dBm
| Talk: -9 dBm
| Shout: 1 dBm
| Scream: 5 dBm

+--------------+--------------+
| Talking Area | Shout Area   |
+==============+==============+
| |Walk-Area|  | |Shout-Area| |
+--------------+--------------+

It may be tempting to have your target speeds at Run and Loudness at
Scream, but this can kill your battery life. For most use cases, we
recommend *Walk* (Target Speed) and *Talk* (Loudness). For demos and
quick response times, we have found that *Run* and *Shout* are the best
for clear communication.

However, we understand that for each use case is different. This is why
we allow an array of settings to choose from for your application with
our Beacons. Target Speed refers to the passing speed of your target
device. Target Speed can also be used to compensate for heavy
interference environments or be used to ensure quick app responsiveness
by increasing the number of BLE advertisements.

With this in mind we bring up a third parameter: Received Signal
Strength Indication (RSSI) or *Measured Power*. **Measured Power** is
the value communicating the expected received signal strength indication
one meter from the beacon, as called RSSI at one meter. You can use RSSI
along with the signal strength received by a device to approximate the
distance of the device from the beacon.

The default measured power for the respective levels of Loudness are:

| Whisper: -76 dBm
| Mutter: -71 dBm
| Talk: -67 dBm
| Shout: -56 dBm
| Scream: -51 dBm

|image4|

####Privacy for your Advertisements BlueCats beacons rotate their
Bluetooth MAC Address to enhance the privacy of your network. This can
be set within the `Web
Manager <http://support.bluecats.com/customer/en/portal/articles/1601784-changing-beacon-settings>`__
and applied with BlueCats Reveal. *Please note* that low (i.e. value of
1 minute) privacy duration values can hinder updating Beacons from some
devices. When the privacy duration is set to 0, the address does not
change.

.. |Walk-Diagram| image:: https://s3-us-west-1.amazonaws.com/github-photos/DeveloperDocs/TargetSpeedOrLoudness/Walk-Diagram.gif
.. |Jog-Diagram| image:: https://s3-us-west-1.amazonaws.com/github-photos/DeveloperDocs/TargetSpeedOrLoudness/Jog-Diagram.gif
.. |Walk-Area| image:: https://s3-us-west-1.amazonaws.com/github-photos/DeveloperDocs/TargetSpeedOrLoudness/Talk-Area.png
.. |Shout-Area| image:: https://s3-us-west-1.amazonaws.com/github-photos/DeveloperDocs/TargetSpeedOrLoudness/Shout-Area.png
.. |image4| image:: https://s3-us-west-1.amazonaws.com/github-photos/DeveloperDocs/TargetSpeedOrLoudness/Settings-Battery-Comparison.png

