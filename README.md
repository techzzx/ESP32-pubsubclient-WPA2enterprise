# ESP32-Devkit pubsubclient demo via WPA2 Enterprise network

This example shows how to use [pubsubclient](https://github.com/knolleary/pubsubclient "Pubsubclient") lib and connect to an WPA2 Enterprise network using the ESP32-Devkit board by using the Arduino environment. You need to install the [enviroment](https://github.com/espressif/arduino-esp32) first.

 Open the file `ESP32-pubsubclient-WPA2enterprise.ino`  in arduino , then change the *ssid* , *user* , *password* , *mqtt server* , *mqtt port* , *subscribe topic* , *publish topic*. Upload the sketch and then it will work.

>[Note]
This example may not work because the development of [arduino-esp32](https://github.com/espressif/arduino-esp32), if it happend , please submit an issue to me , thanks.

 Thanks to [JeroenBeemster](https://github.com/JeroenBeemster/ESP32-WPA2-enterprise) and [0x1abin](https://github.com/0x1abin/pubsubclient/commit/1887f4ba20955acfb06e2c8447ea079413032646).