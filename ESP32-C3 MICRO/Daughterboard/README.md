# [KiCad](https://www.kicad.org/) Daughterboard Starter Project 
### Instructions
1. Extract the ZIP file to a convenient location
2. In KiCad, select "Open Project" and select "ESP32-MicroC3-Daughterboard.kicad_pro"
### Notes
1. This board stackup is based on [Oshpark's 2-layer HHDC](https://docs.oshpark.com/services/two-layer-hhdc/).
2. The connectors, board outline, and mounting hole are all locked to prevent accidental changes that would invalidate your design.
3. I2C pullup is already handled on the main board, so there is no need to add these to your design.
4. All power and logic is 3.3 volt.
5. Use the ground closest to the pin(s) used for best results.  It is best not to connect the grounds together on the daughterboard.
![Daughterboard](https://github.com/Xorlent/ESP32-Boards/blob/main/ESP32-C3%20MICRO/images/ESP32-MicroC3-0.3Daughterboard.jpg)
