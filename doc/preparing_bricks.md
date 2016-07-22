[Dallas Young Makers Club](http://dallasyoungmakers.org/)

# Preparing RCX Bricks

## Verifying a Programmed Brick

If your bricks are already programmed from a previous class, all you need to do is follow the steps below to verify that they are still ready for use.

1. Press the `on/off` button on the unit and observe that it powers on and starts counting up.  If it isn't counting, the firmware may be corrupted or the batteries may be too low and you will need to reflash the brick.
2. If the brick is counting, press `view` 7 times to go past each sensor and motor port and display the battery voltage.  If the voltage is less than 8.4v then the batteries should be replaced.  See replacing batteries below.
3. Your brick is ready for use!

## Reflashing a Brick

1. Power up your Pi or other linux machine where this code has been installed.
2. Connect a USB IR tower
3. Run `./dal-young-makers/tools/flash-menu` if it is not set to launch automatically.
4. Place your RCX brick directly in front of, and facing the IR tower.
5. Choose "flash full firmware" in the menu.
6. Select which programming you would like to flash.
7. Wait for the flash process to complete.  It may take up to 5 minuets.
8. Once complete you can repeat the flash with a new brick.

## Replacing Batteries

If you still have a good flash, but the batteries are low, you can try replacing them in a certain way to preserve the current firmware. Here are the instructions:

1. Make sure the brick is OFF through this process or the firmware will be erased.
2. Gather 6 new AA batteries
3. Carefully remove the cover from the RCX brick
4. Quickly replace each AA battery individually so that only one battery is out at a time.
5. Once all of the batteries have been replaced, put the cover back on and check the verify the Brick/firmware are OK.  If the Brick isn't counting, it will need to be reflashed.
