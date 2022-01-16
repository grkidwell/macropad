# Troubleshooting
## &nbsp;
Link to Adafruit's troubleshooting page
[https://learn.adafruit.com/adafruit-macropad-rp2040/troubleshooting](https://learn.adafruit.com/adafruit-macropad-rp2040/troubleshooting)
## Safe mode
Halts execution of python code.  See [adafruit link](https://learn.adafruit.com/adafruit-macropad-rp2040/circuitpython) for full Safe Mode description
#
1. Hold down reset button 
2. Wait 700ms for yellow flash
3. Press and release reset again
4. Should now see repeating 3 yellow flashes



## Nuke the flash
#
1. Download ["nuke" UF2 image](https://cdn-learn.adafruit.com/assets/assets/000/101/659/original/flash_nuke.uf2?1618945856)
2. Put macropad in bootloader mode (see instructions in Update CP section of this tutorial)
3. Copy UF2 image to RPI-RP2 drive
![Screenshot](img/troubleshooting1.png)

## Stuck in READ only mode
#
1. Try safe mode.
2. Edit/Copy files
3. If this doesn't work, then nuke the flash