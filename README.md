# Simple Bluetooth BLE for the ESP32

This is a very simple evolution of the existing BLE examples in the ESP32 distribution that actually works straight out of the box.

Run the server on one ESP32 and the client on another and you can watch simple messages go from one to the other. 

Invent your own IDs for your services and put whatever you like in the packets (up to 20 bytes) and away you go. 


Note that the device name in the server should be no more than 3 characters if you want to use an ESP32 as the client. I've no idea why this is, but some things you just have to do. 

Created with gateful thanks to [Neil Kolban](https://github.com/nkolban) who created the original code and also wrote a [fantastic guide](https://github.com/nkolban/esp32-snippets/blob/master/Documentation/BLE%20C%2B%2B%20Guide.pdf) to how to use Bluetooth on the ESP32.

Rob Miles