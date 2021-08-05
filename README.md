# MULTIPASS Version 3

![Image of MultiPassV2](https://github.com/nmsr1196/Multi_Pass_3/blob/main/MulitpassInteractive.png)

![Image of MultiPassV2](https://github.com/nmsr1196/Multi_Pass_3/blob/main/MP3_display.png)


The MULTIPASS Version 3 (MPv3) has all the features of the Multipass version 2 with a few extras. 
#### NEW FEATURES: 

- QT Py 2040

- New Top and Bottom 3D models (3 parts)

- Acrylic diffuser

- Multitag

- Badge Holder 

- Nextion 5" programmable display

#### ADDITIONAL FEATURES

- Removable Disc

- Night Light via button

- OLED SSD1306

- Acrylic illumination

- Sound (voice of LeeLoo)

- 0n/off button


#### CODE: 

THIS PROJECT USES CIRCUITPYTHON 6.3.0 VERSION

The code file ‘codeFINAL.py’ has to be changed to ‘code.py’ for the QT Py 2040. Also in the code ignore the two lines 'button'. Its not being used in the code. This code has very slight changes from MPv2. You can use either file. And you can custimize it to your needs.

#### WIRING: 

The wiring connectivity can be found in the 'MP3wiring.fzz' document file.


#### GLUE USED: 

I used hot glue to secure the parts. And just a small bead on the bottom of the QT Py 2040. But, be careful not to let it bleed into
the bottom part. The Nextion display edges were hotglued to the top and back model edges to secure it.

#### 3D PRINTING MODIFICATION: 

As mentioned before, the 3D models for MP3 is different from MPv1 and MPv2. The new models are included.

- The geometry for the top and back parts had to be changed to support the nextion display


#### ACRYLIC: 

- Acylic does not have to be used. A light diffusion 3D material can be used. For this version 2. I used  1/4” pieces.

- The acrylic bar is a different size from MPv2

- The parts are small so the cuts are fast and simple.


#### POWER:

- Due to the nextion display I would suggest usesing a LiPo battery 420mAh or greater.. 

- The battery will be recharged via the power boost500. You can use the Powerboost 500 or 1000.

- 420 mAh LiPo (https://www.adafruit.com/product/4236) You can use a smaller size, Its just what I had at the time.

- Powerboost (https://www.adafruit.com/product/2465)  or if you have a different type of LiPo charger, you can use that.

- Diode - Used a diode to connect to 5 volt pin of the QT Py 2040. Cathode side to 5V pin of QT Py (https://learn.adafruit.com/adafruit-qt-py-2040/pinouts) Cathode


#### BELOW ARE THE PARTS USED:

Many of the parts are found in MPv2

- QT Py 2040 (https://www.adafruit.com/product/4900 )

- Stemma Speaker (https://www.adafruit.com/product/3885)

- 7 Jewel Neopixel (https://www.adafruit.com/product/2859 )  This goes into the lens disc hole

- Adafruit LED Sequins - Emerald Green, Pack of 5 (these are 3 of the lights I used for the rod and the night light) https://www.adafruit.com/product/1756

- Mini On/Off button (https://www.adafruit.com/product/3870) Power button. If you choose to use a different button, hot glue is your friend, or 3D print some to 
  compensate the size.

- Metal Ball Tactile Button (https://www.adafruit.com/product/3347) This is the pushbutton for the night light. 

- 3mm LED (https://www.adafruit.com/product/4202) You can use any type/color of 3mm LED

- Diode  Used to connect between powerboats 5V and 5V pin of QT Py 2040 (see above)

- 2.2K Resistor You can use your own value of resistor. I chose a higher value to try and reduce brightness

- Wire Wrap (https://www.amazon.com/gp/product/B01CK9GZV6/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1 ) I used multiple colors to keep my wiring sanity.

you can use a solid color option (https://www.adafruit.com/product/1446) the choice is yours.

- OLED SSD1306 I2C Display (https://www.amazon.com/Pieces-Display-Module-SSD1306-Screen/dp/B08N6N8L5Q/ref=sr_1_8?dchild=1&keywords=oled+i2c&qid=1622717100&sr=8-8) You can use any version of the ssd1306. I chose this one because of its small footprint and low profile and its wiring connections on one end.

- 3D Material  I had some Prusa Silver PLA. You can use any color/material. I used silver because I did not want the cosplay police coming after me

- The Acrylic I used clear green 1/4” for the stem/rod and lense. Also for the lens, I used 1/4” green. As long as its diffusible, the choose is yours. I left the tape on the bottom of the lens to better diffuse the leds. Or you can adjust the brightness in the code.


 
#### FILES

- MultipassV2_Demo.mov - This shows some of the features of the multipass version 2

- MultiPass_Version2.fzz - Parts drawing and connectivity

- multipass3.wav - Wav file for Leeloo's voice

- Multipass_TOP_V2.stl - 3D model for multipass top

- Multipass_BOTTOM_V2.stl - 3D model for multipass bottom

- Multipass_V2.py - This is the CircuitPython code. You will need to rename this file to 'code.py' and load libraries listed in code.

- Multipass_V2_Rod.stl - This is the acrylic rod for laser cutting. This measures 3.99mm x 40.9mm. You may have to adjust for 3D printing dependant on material.

- Multpass_V2_lense.svg - This is the acrylic rod for laser cutting. This measures 25.8mm. You may have to adjust for 3D printing dependant on material.



