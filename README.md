# Hema Safety App

## Description
It is an Android app which can help you in an emergency situation. In such a case you tap on a big red button which causes the app to send out SMS to your preconfigured contacts/groups without comfirmation. So don’t tap on the wrong button ;-)
PanicTrigger runs in the background and listens for incoming SMS this is why it needs the permission to read your SMS. I won’t read your SMS :)<br/>
If an ingoing SMS contains a specific word AND is from a specific number then an alarm will go off and call the sender of the SMS in one minute. Enough time for you to wake up and realize that the alarm has been triggered.<br/>
Your contact(s) can trigger your alarm with a simple SMS and vice versa. If he/she/they doesn’t have this app he will only see an SMS with the text “Panic” (by default) and your current GPS coordinates. This makes this app useful regardless of if your contact has this app installed or not.<br/>

## Requirements
 - Your phone
 - A connection to your provider
 - Enough credits for a few SMS
## Features
 - AMOLED theme by default
 - Simple interface
 - Triggers an alarm on your friends phone (He/She/They needs to have this app too)
 - More features coming soon…
 - Send last known GPS coordinates within trigger message
 - In case there are no contacts configured call emergency services
 - Contacts grouping
## Coming soon…
## Permissions
- ```android.permission.RECEIVE_SMS``` is needed to receive the emergency SMS
- ```android.permission.SEND_SMS``` is needed to send the emergency SMS
- ```android.permission.ACCESS_COARSE_LOCATION``` is needed for a quick discovery where you are
- ```android.permission.ACCESS_FINE_LOCATION``` if set, try to discover your exact location
- ```android.permission.CALL_PHONE``` is needed to call the sender of the "Panic"-SMS
- ```android.permission.READ_CONTACTS``` is needed for picking contacts (Not used yet)
- ```android.permission.INTERNET``` is needed for downloading map tiles (osmdroid)
- ```android.permission.ACCESS_NETWORK_STATE``` (osmdroid)
- ```android.permission.WRITE_EXTERNAL_STORAGE``` is needed for writing to the tile cache (osmdroid)

<!--stackedit_data:
eyJoaXN0b3J5IjpbNzIyMzM3MjU4XX0=
-->
