# GY_LCD_MLX90640
Firmware update method:
1、Open GY_DOWNLOAD_V1.0.exe
2、Click "open" to select the firmware
3、The computer connects to the product via USB，Select the COM PORT
4、At the same time, press the confirm key and add key of the product，Waiting for the screen to display "Waiting connect..."
5、Click "START" of PC software，Wait for the firmware update to complete

Version: V1.5
1. Change the Show function of the setting item to 1-3.Upgrading from a lower version to that version requires the user to change this value.

Version: V2.0

1.Increase unit conversion.
2.Added icon feature options.
  Short press the confirm button-->Press the add/subtract button to select the function options--> Press the confirm button to enter the item
  -->Press the add/subtract button to change the item value-->Long press the confirm button for 3 seconds to return to normal operation mode.
  ![image](https://github.com/GYelectronic/GY_LCD_MLX90640/blob/master/images/function.png)
  ![image](https://github.com/GYelectronic/GY_LCD_MLX90640/blob/master/images/color.gif)
  
Version: V2.2
Add the forehead temperature measurement function, short press the confirm key to enter the menu, right click mode B, confirm the key to enter the function, press the add or subtract key to correct the temperature.
Reasons for inaccurate measurement:
1.The temperature fluctuates greatly.It takes 5 minutes for the device to stabilize after starting up.
2.Measurement distance, ambient temperature changes lead to temperature measurement is not accurate.At this point, E can be modified by
adding or subtracting keys, and also can be changed appropriately (emissivity, human emissivity is generally 0.95~0.98).
3.The abrupt change in the measured person's environment leads to inaccurate temperature measurement.Keep the person in the measuring environment for more than 5 minutes before taking the measurement.

Version: V2.3
  Fixed a BUG where no image was uploaded to upper computer due to product temperature rise
Note: Do not update the firmware when the temperature of the product is too high. Update the firmware when the temperature is lower than 37 ° C.

Version: V2.4
  1.To optimize the image display.
  2.Optimize the mode of measuring temperature, low temperature of human body temperature measurement.

