### Send SMS Android
**Overview**
- To send a short message (SMS) one can use:
1.  SmsManager API
2.  Devices Built-in SMS application
- The scripts in this repository applies the **SmsManager** API
**Syntax**
```java
SmsManager API
SmsManager smsManager = SmsManager.getDefault();
smsManager.sendTextMessage("phoneNo", null, "sms message", null, null);
```
**Original Source + More Info**
- See ***[TutorialsPoint](https://www.tutorialspoint.com/android/android_sending_sms.htm)***
