# WARNING  This is a not revertable procedure and it will render your instrument useless

1. Download and install the flash program for Windows from https://www.ti.com/tool/LMFLASHPROGRAMMER

2. Contact Dataq via email for the firmware, eraseeeprom.bin

3. Remove the USB cable from your device and PC, and remove power supply to the device if it gets power from external power supply

4. Plug the USB cable to PC (the other end should NOT connect to the device at this point)

5. Force the device into firmware upgrade mode...
   - For device without external power supply, plug in the USB cable to the device while holding the button down. The LED should be solid WHITE, if not go back to step 2.
   - For device with external power supply, such as DI-4718B and DI-4730, push and hold the button while powering up the device.  The LED should be solid WHITE, if so, connect the USB cable to the device, if not go back to step 2. 

6. Start LMFlash.exe program installed in step 1. The startup page will be exactly as below <br/>
![alt text](https://www.dataq.com/resources/repository/lmflash1.png)

7. Choose the Program Tab. Navigate to your download directory, click on the eraseeeprom.bin file from step 2 <br/>
![alt text](https://www.dataq.com/resources/repository/lmflash2.png)

8. # WARNING  The next step will render your instrument useless!!!!
   
9. Press the Program Button at the lower left corner. When it finishes, the device should be FLASHING like a Christmas tree light

10. Now you can dispose your instrument
