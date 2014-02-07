# PubSubClient with AdaFruit CC3000 library support 
This is hacked up version of Nicholas O'Leary's PubSubClient that works with the AdaFruit CC3000 breakout board (http://learn.adafruit.com/adafruit-cc3000-wifi/overview) and the AdaFruit CC3000 library (https://github.com/adafruit/Adafruit_CC3000_Library).

I did this really fast and have only tested the connect and publish features (which is what I recently needed). On the plus side, this works fairly reliably. 

## Example

To see how to get started, check the simple temperature publish example: [uno_cc3000_mqtt_publish.ino](https://github.com/justinribeiro/pubsubclient/tree/master/PubSubClient/examples/adafruit_cc3000_publish/uno_cc3000_mqtt_publish.ino)

The biggest difference is that my version will only take an IP address and requires you pass both the Adafruit_CC3000 and Adafruit_CC3000_Client (as opposed to say just the YunClient or EthernetClient in the regular version of the lib).

## Warning: this library won't work for other ethernet/wifi devices

This version of PubSubClient is stripped down to the barebones to make it work with AdaFruit's CC3000. If you have other wifi or Ethernet shields, this version WILL NOT work.
