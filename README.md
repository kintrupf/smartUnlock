#SmartUnlock

SmartUnlock is a set of scripts (aka flows), that run in Automagic Premium on Android phones.
They enable you to keep your phone unlocked as long as possible when it is safe to do so.
So in many cases you don't need to enter your PIN code when switching the display on.
"Safe" in this context means the phone is in a "trusted" context like connected to a certain WLAN or Bluetooth device or within a defined location.

#Pre-requisites

- An Android phone with Android 4.x
- [Automagic Premium](https://play.google.com/store/apps/details?id=ch.gridvision.ppam.androidautomagic)

#Installation
Download the flows from GitHub and import them into Automagic.

##Activating the flows
After installing the flows in Automagic Premium you only need to do zwo things. First edit the flow **SmartUnlock_setPIN** to set a PIUN or password for your device. You might also change the action to **Set Lock Pattern State** if that works on your device. 
Then execute the flow **SmartUnlock_initSmartUnlock**. This will automatically enable or disable the proper SmartUnlock flows and creates the needed global variables. SmartUnlock is now ready and should display a notification icon (a lock).
You can expand the notification in the notification drawer und access the SmartUnlock settings.


#FAQ
