# SSD1306_SPI
C Libraries for supporting SPI based OLED display (SSD1306)


Originally Library was built by Tilen Majerle, in 2015. Which was later modified to support SPI interfacing based OLED displays. The library supports STM32F103XX boards. 

The Pins connected to Displays and to corresponding Pins in MCU

**Display -----> MCU**
D0 ------> A5
D1 ------> A7
RES ------> A4
DC ------> B1
CS ------> B0

**Note:** The Code is developed in STMCube IDE and tested for STM32F103XX (Bluepill). 
Remeber to Initialize SPI1 Ports which corresponds to A5 and A7. Rest pins as GPIO outputs. 

Add ssd1306_spi.c and fonts.c in src folder.
and ssd1306_spi.h and fonts.h in Inc folder.

