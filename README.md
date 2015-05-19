# snoozeLib
Low Power Mode Library for Arduino

SnoozeLib: This Arduino Library make the use of Low Power Mode very Easy. This library Helps you make your arduino based microcontroller use the Low Power Mode it use the WatchDog Functionallity and sleep the CPU clock for low consumption.
 
Based on the library Narcoleptic: [https://code.google.com/p/narcoleptic/](https://code.google.com/p/narcoleptic/)

This library is tested on Arduino UNO and Arduino Mega(atmel 328p and atmel Mega 2560).

## Reference

- snooze(long milliseconds)
 this function sleep the CPU for the specified Milliseconds or if the function _wakeup_ is called. Example of use:
 ```c
  snoozeLib.snooze(10000);//Sleeps for 10 seconds.
 ```

 - wakeup()
 this function wake the CPU and disable the WatchDog.
 ```c
   snoozeLib.wakeup();
 ```
 
---
License GNU General Public License v3.0. 

