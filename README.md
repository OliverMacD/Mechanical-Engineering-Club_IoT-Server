# Mechanical-Engineering-Club_IoT-Server
This repository handles all information regarding the IoT server for the Boise State Mechanical Engineering Club


## Main Use
### How to Start & Run Main Computer and IoT Dashboard
    1. Turn on Computer
    2. When the red exclimation mark appears:
        2.1. Press Ctrl+L to reach the boot menu
        2.2. Hit Escape
        2.3. Select MMC for the boot Option
    3. Connect Laptop to internet if autoconnect fails
    4.
### How to Connect Devices to IoT Server and Publish to MQTT Broker
TODO
### How to Connect other Devices to IoT Dashboard
TODO

## Download Links
- ZeroTier Download
  - https://discuss.zerotier.com/t/guide-zerotier-gui-on-linux-mint-ubuntu/9447
  - Use "sudo apt-get installpkg-config" if "make" fails
- Mosquitto Download
  - [https://mosquitto.org/download/](https://randomnerdtutorials.com/how-to-install-mosquitto-broker-on-raspberry-pi/)
- Node-Red Download
  - https://nodered.org/
- Download PostgreSQL Download
  - https://www.geeksforgeeks.org/install-postgresql-on-linux/
- Adding users and setting user permissions
  - https://nodered.org/docs/user-guide/runtime/securing-node-red

## System Information
### Computer Software
The following programs are installed on the ME Clubs main laptop with details about their uses and implementations:
- Ubuntu 22.04
  - Linux Distribution
- Git
  - Just for npm
- ZeroTier
  - Decentralized network server to allow remote access to main computer and connect periferals on different networks to MQTT and IoT Network
- Node-Red
  - IoT API and Dashboard
- Mosquitto
  - MQTT Broker
- PostgreSQL
  - SQL Server and Manager
### Computer Hardware
The ME Club IoT Server runs off a Lenovo N23 Chromebook turned Linux system with the following specs:
- Intel Celeron N3060
- 11.6" TN Display
- 45 Wh Battery
- Unknown DDR3
- 16gb eMMC
- 720p Webcam
- 2x USB 3.0
- HDMI
- SD Card Reader
- Combo Mic & Audio Jack
- 802.11 AC (2x2)
### Raspberry Pi Information
The ME Club IoT Server currently recieves data from an _________ Raspberry Pi ____ which acts as a node on the ZeroTier network. The device has the following software and hardware:
#### Software
- Ubuntu Unknown
  - Linux Distribution
- Git
  - Just for npm
- ZeroTier
  - Decentralized network server to allow remote access to main computer and connect periferals on different networks to MQTT and IoT Network
- Mosquitto
  - MQTT Broker
#### Hardware:
- Unknown (Final Device Yet To Be Chosen)

## Other Useful Links
- Node-Red Dashboard Tutorial
  - https://randomnerdtutorials.com/getting-started-node-red-dashboard/
  - [https://www.youtube.com/watch?v=X8ustpkAJ-U](https://flows.nodered.org/node/node-red-dashboard)
- Installing Linux on Chrome
  - https://dbtechreviews.com/2018/09/how-to-install-ubuntu-on-chromebook-and-remove-chromeos/
- Security Information
  - https://nodered.org/docs/user-guide/runtime/securing-node-red
- If Node-Red Won't Connect over ZeroTier
  - https://docs.zerotier.com/zerotier/troubleshooting/
  - https://vitux.com/how-to-block-allow-ping-using-iptables-in-ubuntu/#:~:text=If%20any%20of%20the%20rules%20is%20blocking%20ping,with%20the%20following%20command%3A%20%24%20sudo%20iptables%20-F
- Node Red Service on Linux PC
  - Service File Contents
    - https://discourse.nodered.org/t/unit-file-nodered-service-does-not-exist/30271/4
  - Making Service File
    - https://www.howtogeek.com/687970/how-to-run-a-linux-program-at-startup-with-systemd/
  - Starting Service File
    - https://nodered.org/docs/getting-started/raspberrypi
- MQTT SetUp & Testing
    -  https://randomnerdtutorials.com/how-to-install-mosquitto-broker-on-raspberry-pi/
    -  https://randomnerdtutorials.com/testing-mosquitto-broker-and-client-on-raspbbery-pi/
    -  https://randomnerdtutorials.com/esp32-mqtt-publish-subscribe-arduino-ide/
    -  https://randomnerdtutorials.com/esp32-mqtt-publish-subscribe-arduino-ide/
- Using SQL in Node Red to Data Log
    - https://www.youtube.com/watch?v=dPFkkQTNPso
    - https://flows.nodered.org/node/node-red-contrib-postgresql
