# IoTWorkshop
This will be a repository of all the sample programs I use for the IoT workshop


# Setting up Arduino IDE for Programming NodeMCU, Wemos or any other ESP basd devices.

1. Download Arduino IDE.
2. Open you IDE and click on "File -> Preferences".
3. In  "Additional Boards Manager URLs" add this line and click on "OK":
  "http://arduino.esp8266.com/stable/package_esp8266com_index.json"
4. Go to "Tools -> Board -> Boards Manager", type "ESP8266" and install it.
5. Go again to "Tools -> Board" and select "Generic ESP8266 Module".

# Installing the driver for CH340G Driver 

1. Go to this website https://wiki.wemos.cc/downloads and download the driver for windows/mac.
2. Install the driver then restart the laptop for the setting to take effect.

# Installing the library for Blynk Support

1. Open you IDE and click on "Sketch -> Include library -> Manage Libraries".
2. In the Library Manager, search for Blynk.
3. Click on it and install. 
4. Restart your Arduino IDE for the changes to take effect. 

# Installing the library for BMP180 Temperature Pressure senssor for Weather Monitoring System Project

1. Open you IDE and click on "Sketch -> Include library -> Manage Libraries".
2. In the Library Manager, search for BMP180.
3. Click on the first link "Adafruit-BMP085-Library" and install. 
4. Restart your Arduino IDE for the changes to take effect. 

# Programming the device

1. Connect the device.
2. Open Arduino IDE
3. Go to "Tools -> Board -> Select teh board which you're using".
4. Select "Flash size -> 4M (1M SPIFFS)"
5. CPU Frequency -> "80 MHz"
6. Upload Speed -> "115200"
7. Select the COM Port which appears on the list "COMX"







