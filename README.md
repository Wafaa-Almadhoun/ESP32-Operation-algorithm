# ESP32-WROOM-32-module-operation-algorithm

## Table of contents
* [Introduction](#Introduction)
* [Technologies](#technologies)
* [Components required](#Components-required)
* [Algorithm](#algorithm)


## Introduction

   ESP32 is a series of low-cost, low-power system on a chip microcontrollers with integrated Wi-Fi and dual-mode Bluetooth.the modules is 
   a family of ESP32-based modules with some integrated key components, including a crystal oscillator and an antenna matching circuit. 
   The modules constitute ready-made solutions for integration into final products. If combined with a few extra components, 
   such as a programming interface, bootstrapping resistors, and pin headers, these modules can also be used for evaluation of ESP32’s functionality,
   in our case we use WROOM module this is a basic and commonly adopted ESP32 module with the ESP32-D0WDQ6 chip on board. It was the first module of 
   the WROOM / WROVER family released to the market

## Technologies
Project is created with:
* Arduino IDE 1.18.15 [To Downloud](https://www.arduino.cc/en/software)
	
## Components required
1. ESP32-WROOM-32-module
2. Micro-USB Cable
3. computer with internet access


## Algorithm

step 1 : Read the data sheet  of  ESP32-WROOM-32 from [here](https://espressif.com/sites/default/files/documentation/esp32-wroom-32_datasheet_en.pdf)

step 2: Open the Arduino IDE and connect the ESP32 with your computer 

step 3:  we need to upload the board packge ,from file  bar choose prefrence.

step 4: then copy and paste this link 'https://dl.espressif.com/dl/package_esp32_index.json'
![3](https://user-images.githubusercontent.com/64277741/180612981-f50d4711-aeed-46a4-b8d0-1767b16e5494.PNG)

step 5: after that from tools>Arduino board> board manger and search on esp32 to install the board

step 6: Now click on tools>board > ESP32 Arduino and choose WEMOS D1 MINI ESP32.

Step 7: open file>exampl > 01.Basics > blink > then run the code .

step 8: after finished compuling we should select tools> our port, COM3

step 9: uploud the code to ESP32 then the LED will Blink ! 

