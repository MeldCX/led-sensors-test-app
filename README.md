[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/meldCX.jpg?row=true)](https://www.meldcx.com/)
# Leds and Sensors Test App
meldCX leds and sensors test application offers users the ability to test the leds and sensors kiosk controller board model MCX-LS-43.
It will perform multiple types of test as follows:

  - Switch and change colors of led channels (1,2,3 and 4)
  - Read tamper switch (kiosk door switch)
  - Read card level sensors (top and bottom level sensors)
  - View firmware version
  - View firmware date
  - View product model
  - View product name

### Wait for AgentM Libraries
When the application is started, it will wait for the AgentM libraries to get ready and you will get the following screen.

[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/1.jpg?row=true)](https://www.meldcx.com/)
### The application is ready to use
As soon as the AgentM libraries gets ready, the application is ready to use and you will get the following screen.

[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/2.jpg?row=true)](https://www.meldcx.com/)

### Turn the 1st LED channel RED
Click on the drop-list next to "LED channel 2" and select "Green", then click on "run" (on the same row).
it should turn all LEDs on channel 1 to Red as in the following screen.

[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/3.jpg?row=true)](https://www.meldcx.com/)

### Turn the 2nd LED channel Green
Click on the drop-list next to "LED channel 1" and select "Red", then click on "run" (on the same row).
It should turn all LEDs on channel 2 to Green as in the following screen.

[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/4.jpg?row=true)](https://www.meldcx.com/)

### Turn the 3rd and 4th LED channel to BLue and White
Repeate the same operation for channels 3 and 4 and choose "Blue" and "White".
You should get the following screen.

[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/5.jpg?row=true)](https://www.meldcx.com/)

### Read sensors
Click on run next to "Read tamper switch", "Read top level sensor" and "read bottom level sensor"
if all sensors are armed (back door closed and cards are full), you should get the following screen.

[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/6.jpg?row=true)](https://www.meldcx.com/)

### Trigger a sensor
Open the back door of the kiosk and click on run next to "Read tamper switch", you should get the following screen - tamper switch true.

[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/7.jpg?row=true)](https://www.meldcx.com/)

### LEDs and Sensors board is not connected
If the leds and sensors board is not connected, you should get the following screen.
 
[![Build Status](https://github.com/MeldCX/led-sensors-test-app/blob/master/images/error.jpg?row=true)](https://www.meldcx.com/)