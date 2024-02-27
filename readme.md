# Flipper Zero: Gameboy Link Port Module

![Gameboy link port module](images\Image.jpeg)

This is a module I worked on as a project to learn about PCB design, but to also learn about KiCAD, which is the program that was used to create this. I used [GAME BOY Pokemon Trading MALVEKE](https://github.com/EstebanFuentealba/Flipper-Zero-Game-Boy-Pokemon-Trading) to create this. Check is out because he is a way smarter guy than I. 

I use his GPIO layout so you will want to do the same on your flipper zero. If you use his Pokemon app in [flipper.net](https://lab.flipper.net/apps/pokemon) then it will be the under "Select Pinout" > "Original".

Copied shamelessly off of his Github.
![GPIO Layout](images\GPIO-GBPIN_light-v2.png)

| Cable Game Link (Socket) | Flipper Zero GPIO 
| ----------- | ----------- |
| 6 (GND) | 8 (GND)
| 5 (CLK) | 6 (B2)
| 3 (SI) | 7 (C3)
| 2 (SO) | 5 (B3)

## Bill of Materials (BOM)

| Material | Link
| ----------- | ----------- |
| Resistor - 3.3k OHM 1% 1/10W 0603 SMD | [Link](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/RMCF0603FT3K30/1761032) (Digikey)
| Resistor - 150 OHM 1% 1/10W 0603 SMD | [Link](https://www.digikey.com/en/products/detail/walsin-technology-corporation/WR06X1500FTL/13239274) (Digikey)
| LED - Clear Red 2.2V 0603 SMD| [Link](https://www.digikey.com/en/products/detail/inolux/IN-S63ATR/7604934) (Digikey)
| 4 Pin Connector Header | [Link](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/61300411121/4846827) (Digikey)
| Gameboy Link Port | [Link](https://www.aliexpress.com/i/3256803930669143.html?gatewayAdapt=4itemAdapt) (AliExpress)