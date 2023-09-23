# Captive Portal

   ## About this project
   ### WiFi captive portal for the NodeMCU (ESP8266/ESP32 Module) with DNS spoofing.
  - A login page will appear when someone connects to this "JioNet@St_Joseph_Inst"(Its passwd free).
  - The username and passwd entered my the user in login page gets collected in `/creds`.
  - The built-in LED will blink 3 times after the login process is completed by someone.<b>

```diff
! Stored Usernames and Password gets deleted when you power off/on the device!!!
```
<b>Note: You can see the creds in <a>"**172.0.0.1**<a>/creds</a>"

# Installation `windows` `linux` `mac`

1. Open your <a href="https://www.arduino.cc/en/main/software">Arduino IDE</a> and go to "File -> Preferences -> Boards Manager URLs" and paste the following link:
``http://arduino.esp8266.com/stable/package_esp8266com_index.json``
2. Go to "Tools -> Board -> Boards Manager", search "esp8266" and install esp8266
3. Go to "Tools -> Board" and select you board"
4. Download and open the sketch "<a href="https://github.com/JuSTinMrp/Captive_Portal_ESP8266/blob/main/NodeMcu-ESP8266_Fake_sign_in/NodeMcu-ESP8266_Fake_sign_in.ino"><b>Captive_Portal.ino</b></a>"
5. You can modify the code according to your need!!!
6. Upload the code into your board.
7. Press rst button or power off/on the device again


## Disclaimer
- This project is for testing and educational purposes. 
- Use it only against your own networks and devices. 

