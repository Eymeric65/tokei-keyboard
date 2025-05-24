# tokei-keyboard
Official repository of the Tokei split keyboard.

This repository is split in the different component in order to make a working Tokei Split keyboard.

*If you are searching the kicad library used in this keyboard you should go to [this repository]*

## Kicad / PCB 

If you directly want to order your board you should directly check [JLCPCB production archive](/kicad/OUTPUT/final-JLCPCB.zip)

Otherwise Kicad project is divided in three :
- The left half
- The right half
- The paneliser to reunion both for production

Electrical output is stored into the **`JLCPCB`** directory, CAD related output is stored in **`CAD`** folder (don't hesitate to check)

## firmware

The `firmware` folder contain ready to flash files in order to test right away the keyboard.

## ZMK

The `zmk-config` file is a direct copy of my `zmk-config` fork for this keyboard. It is the base to the build of the keyboard.

## CAD 

The `CAD` folder contain everything related with the 3D printed cover. I work with Alibre but you can find the ready-to-use `.step` in the `CAD/export` folder. 




