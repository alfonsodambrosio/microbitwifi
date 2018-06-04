Alfonso microbit wifi

Blocchi
1. Initialize WiFi IoT 
inizializza wifiper microbit

alfonso.initializeWifi()
2. Set WiFi
connette wifi alla rete domestica

alfonso.setWifi("alfonso", "12345678")
Here we take "alfonso" as router SSID and "12345678" as router password.

3. Set WiFi hotspot
Configure il wifi come hotspot.

alfonso.setWifiHotspot("alfonso", "12345678")
For the hotspot, here we take "alfonso" as SSID and "12345678" as password.

4. Connect to ThingSpeak
Upload data to ThingSpeak

alfonso.sendThingspeak("asdasdasdasdasdasd", 0, 0)
Here we take "asdasdasdasdasdasd" as the ThingSpeak key, 0 as field1 value and 0 as field2 value.

5. Connect to IFTTT
Trigger the IFTTT cloud event such as email, sms and so on.

    alfonso.sendIFTTT(
    "asdasdasdasdasdasd",
    "email",
    0,
    0
    )
Here we take "asdasdasdasdasdasd" as IFTTT key, email as event name, 0 as value1 and 0 as value2.

License
MIT

Supported targets
for PXT/calliope
for PXT/microbit
(The metadata above is needed for package search.)
