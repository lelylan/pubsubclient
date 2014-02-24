# PubSubClient with AdaFruit CC3000 library support 
This is hacked up version of Nicholas O'Leary's PubSubClient that works with the AdaFruit CC3000 breakout board (http://learn.adafruit.com/adafruit-cc3000-wifi/overview) or the Wicked Device WildFire (http://shop.wickeddevice.com/product/wildfire/) and the AdaFruit CC3000 library (https://github.com/adafruit/Adafruit_CC3000_Library).

Publish and subscribe are working.

## Example

To see how to get started, check the simple temperature publish example: [uno_cc3000_mqtt_publish.ino](https://github.com/nathanchantrell/pubsubclient/blob/master/cc3000_PubSubClient/examples/adafruit_cc3000_publish/uno_cc3000_mqtt_publish.ino)

Or for the WildFire: [wildfire_cc3000_mqtt_publish.ino](https://github.com/nathanchantrell/pubsubclient/blob/master/cc3000_PubSubClient/examples/wildfire_mqtt_publish/wildfire_mqtt_publish.ino)

The biggest difference is that this version will only take an IP address and requires you pass both the Adafruit_CC3000 and Adafruit_CC3000_Client (as opposed to say just the YunClient or EthernetClient in the regular version of the lib).

## Warning: this library won't work for other ethernet/wifi devices

This version of PubSubClient is stripped down to the barebones to make it work with AdaFruit's CC3000 library. If you have other wifi or Ethernet shields, this version WILL NOT work.
