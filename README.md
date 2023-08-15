# MCU WiFi Manager

Lang   : Micropython 
Tested : 1.8 and 1.9.3

## WiFi manager for ESP8266 - ESP12 - ESP32 for micropython 

### Main Features:
- Web based connection manager 
- Save wifi password in "wifi.dat" (csv format) 
- Easy to apply 

### Usage:
Upload main.py and wifimgr.py to ESP. 
Write your code into main.py or import it from main.py. 

### Logic:
- Step 1: Check "wifi.dat" file and try saved networks/passwords.
- Step 2: Publish web page to configure new wifi. 
- Step 3: Save network/password to "wifi.dat" file. 
- Step 4: Run user code.

![alt text](https://github.com/tayfunulu/WiFiManager/blob/master/WiFi_Manager.png)

**web server based on code of CPOPP - https://github.com/cpopp/MicroPythonSamples
