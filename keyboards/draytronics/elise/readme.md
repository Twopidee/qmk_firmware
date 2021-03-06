# ELISE

![elise](https://www.draytronics.co.uk/wp-content/uploads/2021/04/repository-open-graph-template.png)

A open source, low cost 65% keyboard PCB with USB-C, ESD protection, RGB underglow and XD68 case / plate compatability.  Designed in the UK. 
More info / sales / PCB designs available at [draytronics.co.uk/elise](https://draytronics.co.uk)

* Keyboard Maintainer: [Blake Drayson](https://github.com/ghostseven)
* Hardware Supported: ELISE PCB / ATMega32U4
* Hardware Availability: [draytronics.co.uk](https://draytronics.co.uk)


Entering DFU mode (to allow flashing):

 - Pressing the reset button on the back of the board when it is plugged in will enter DFU.
 - Holding down the ESC key whilst plugging in the keyboard will enter DFU.
 - If you have one of the provided keymaps flashed, then pressing FN-Tab will enter DFU.
    
Make example for this keyboard (after setting up your build environment):

    make draytronics/elise:default

Flashing example for this keyboard:

    make draytronics/elise:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).


![elise-pcb-top](https://www.draytronics.co.uk/wp-content/uploads/2021/04/Draytronics-Elise-PCB-V1-top.png)

![elise-pcb-bot](https://www.draytronics.co.uk/wp-content/uploads/2021/04/Draytronics-Elise-PCB-V1-bottom.png)
