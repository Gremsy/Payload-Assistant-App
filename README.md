# Payload-Assistant-App
The Android app to support Gremsy's payload 

+ INSTALLATION (Copy SD Card)
---------------------------
- Unzip file 'Payloads_Assistant.apk'
- Copy file to microSD card
- Insert SD card to your Herelink
- Click to notification - "New SD card detected"
- Select "USE as portable storage" and confirm NEXT and DONE
- Re-open notification area, click to "SD Card for transferring photos and media"
- Click to Payloads_Assistant.apk
- Allow external sources if necessary
- Install, open app, Confirm "drawing over other apps"
- Close app and Restart

---------------------------
+ INSTALLATION ADB (Connect ADB USB Or Wifi)
- Download tools adb android : https://developer.android.com/tools/releases/platform-tools
- adb devices (check devices connect) 
- Ex: 
- $: adb devices
- $: List of devices attached
- $: e91a992b        device	or	(192.168.12.66:5555      device)(wifi)


- adb install
- $: adb -s e91a992b install .\Payloads_Assistant.apk 	or	(adb -s 192.168.12.66:5555 install .\Payloads_Assistant.apk) (wifi)
Performing Streamed Install
Success

==> Note: On Screen confirm
(Install via USB ==> Install)

