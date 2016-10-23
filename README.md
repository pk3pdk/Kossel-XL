# Kossel-XL
Kossel XL Marlin new Menu

create Folder KXL_new and copy the Arduino Files into it

I´ve made changes to the "prepare menu" Many of these changes are based on the dimension of
my kossel XL. So check the dimensions of your Delta. This is really important!!!
Changes are made in ultralcd.cpp and language.h
including:
"Load Filament"
"Unload Filament"
"Tower X/Y/Z" for setting up the endstops, the Nozzle will go into each corner of the towers. Please Auto Home before!!
"Plate 0" means Z=0 on the middle of build plate. Please Autohome before!!
"Preheat PETG" splitted in hotend and bed, just for easy filament change
Very important! the movement menu for X/Y/Z Tower and plate 0 will need an "Auto Home" first!!!! I did not include an Auto Home with these menus! really always do Auto Home first!!!!!!


I´m using a full graphic smart controller. Change the LCD if needed

To find the changes I´ve made search "in all sketches" for "p_k_3pdk" and you will find all changes I´ve made.
