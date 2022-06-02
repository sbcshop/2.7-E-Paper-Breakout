# 2.7-E-Paper-Breakout

<img src= "https://github.com/sbcshop/2.7-E-Paper-Breakout/blob/main/images/img0.jpg" />

<img src= "https://github.com/sbcshop/2.7-E-Paper-Breakout/blob/main/images/img1.jpg" />

### 2.7-inch e-paper display is an Active Matrix Electrophoretic Display(AMEPD) with 264*176 resolution respectively, comes with SPI interface.e-paper breakout's comes in two variant with the ability to display black-and-white or black-white-red graphics. Without power, your image will persist endlessly - display it, then turn off the electricity. These e-paper display modules don't require any power after they've been updated, and they may even be turned off completely, with the content remaining on the screen indefinitely. These e-ink screen is ideal for solar or battery-powered devices

## Connections

<img src= "https://github.com/sbcshop/2.7-E-Paper-Breakout/blob/main/images/img2.JPG" />

## Code
### First of all, you need to enable SPI in raspberry pi, for this you need to go ```sudo raspi-config ``` then go to "interface options->SPI->yes->press enter" There are two folder in GitHub repository
 * E_Paper_B&W (Black & White Color)
   * e_paper_2_7.py        -> Run this file
   * lib_2inch7_e_paper.py -> Library of 2.7 inch e-paper 
   * e_paper_2_7_rfid.py   -> Run this file if you want to connect RFID HAT (application)
   
 * Paper_Red_Color (Red & Black Color)
   * e_paper_2in7_redColor.py  -> Run this file 
   * lib_2inch7_ec_paper.py    -> Library of 2.7 inch e-paper red color 
   * e_paper_2in7_color_air.py -> Run this file if you want to display values of Air monitoring HAT or breakout (application)
   * pms_a003.py               -> Library of air monitoring HAT or breakout
   
## For e-paper datasheet go below link:-

https://www.good-display.com/product/236.html

https://www.good-display.com/product/235.html
