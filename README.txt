HOW TO MAKE AN ANDROID-CONTROLLED ARDUINO BLUETOOTH CAR

1. Secure the materials
2. Connect the Bluetooth Module to the Arduino (see Arduino-Bluetooth Connection Diagram.jpg)
3. Connect the L298N Motor Driver to the Arduino (see Arduino-L298N Motor Connection Diagram.jpg)
4. Assemble the 2WD Chassis Kit (You can use an old RC Car's chassis instead of buying the 2WD kit)
5. Connect the Arduino to your computer. Make sure the RX pin on the Arduino isn't connected or you won't be able to upload to the Arduino. 
6. Upload the Arduino code (See Bluetooth_Arduino_Motor_Code.ino inside the Arduino Bluetooth Motor Code folder)
7. Connect the RX Pin on the Arduino after uploading the code
7. Upload the Android app to your smartphone if you're using Android Studio. If you're not into that kind of shit, just install the app with the .apk file inside the Android App APK File folder.
8. Put in the batteries for the L298N Motor Driver. When powered on, the Motor Driver's LED should glow.
9. Open the Android App
10. Press the "Connect to Bluetooth Device Device" button. If your bluetooth is turned off, it will ask permission to turn it on.
11. After bluetooth is turned on, press the button again.
12. After a second or two, the Bluetooth Module's LED should stop blinking, indicating a connection has been made
13. DONE.
