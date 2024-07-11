# voxelabaquila_bigtreetech

Upgrade notes for replacing aquila stock motherboard+lcd screen for BTT parts

BTT SKR MINI E3 v3.0  
https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/master/hardware/BTT%20SKR%20MINI%20E3%20V3.0/Hardware/BTT%20SKR%20MINI%20E3%20V3.0%20user%20manual.pdf  
Had to solder some wires  
Fan connections:  
https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/issues/585  
The correct fans wiring are  
FAN0: Prints part cooling  
FAN1: Hotend fan   
FAN2: board cooling fan  
Touchscreen cable: double check PWR and RST(dangly end). The connections are labeled on the back side of the board.  

BTT TFT35-E3 V3.0.1  
https://github.com/bigtreetech/BTT-TFT35-E3-V3.0/blob/master/BTT%20TFT35-E3%20V3.0%20User%20Guide.pdf  
Connect touchscreen connection to "TFT"   
Only need the one LCD connection for Aquila, its EXP3(CR-10 LCD)  

Crosslink  
SKR 1.3 / 1.4 - TFT35 Display Installation and Marlin 2 0 configuration  
Gives helpful info on wiring for display at timestamp  
https://youtu.be/DodRRgZf5Lo?t=334  

Teaching Tech  
BTT TFT35 dual mode touch screen guide  
https://www.youtube.com/watch?v=l1Putn10_Ek  


# Notes on previous modifications:
- Added CRTouch
- Reversed Extruder Direction(unknown why necessary)
- Firmware for board - https://github.com/haqbany/Bigtreetouch-SKR-Mini-E3V3.0/releases v5.0
-   could not use stock SKR Mini E3 V3.0 firmware variations(printer not found)
-   also using haqbany preheat functions not working
- Latest firmware for TFT35
