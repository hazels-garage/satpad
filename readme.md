![GitHub](https://img.shields.io/github/license/hazels-garage/satpad?label=%20&logo=creativecommons&logoColor=%23ffffff&style=flat-square)
<a href="https://discord.gg/jP6hvgNN8r">
  ![Discord](https://img.shields.io/discord/989552667330228374?color=%237289da&label=%20&logo=discord&logoColor=%23fff&style=flat-square)
</a>
<a href="https://shop.hazel.cc/products/satpad">
 ![Hazel's Garage](https://img.shields.io/badge/-Purchase-%23000?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAABGdBTUEAALEQa0zv0AAAACBjSFJNAACHDwAAjA8AAP1SAACBQAAAfXkAAOmLAAA85QAAGcxzPIV3AAABCGlDQ1BJQ0MgUHJvZmlsZQAAKM9jYGBckZOcW8wkwMCQm1dSFOTupBARGaXAfoeBkUGSgZlBk8EyMbm4wDEgwIcBJ/h2DagaCC7rgsxiIA1wpqQWJwPpD0Acn1xQVAJ0E8gunvKSAhA7AsgWKQI6CsjOAbHTIewGEDsJwp4CVhMS5Axk8wDZDulI7CQkNtQuEGBNNkrORHZIcmlRGZQpBcSnGU8yJ7NO4sjm/iZgLxoobaL4UXOCkYT1JDfWwPLYt9kFVaydG2fVrMncX3v58EuD//9LUitKQJqdnQ0YQGGIHjYIsfxFDAwWXxkYmCcgxJJmMjBsb2VgkLiFEFNZwMDA38LAsO08APD9Tdt4gbWmAAAACXBIWXMAABJ0AAASdAHeZh94AAABC0lEQVQ4T2MAgv9kYqyCxGBMQUtFVwwxLBhVwEDG+n934PL/HQFLUMSxYEzBJp85/8td+/97aUf9jzcv+s/HIQgWZ2JkQlaH0MDOwgG2rcJtAhjXek773+G/+D8POz9QEzOyJhBGcMwVnf83es+GawThNr8FYDlGBka4OihGcEzlHcEaS1x6wJoq3Sf9L3PtQ1aMjBEcNTH9/xoShv9jzPL/13lOB2tKta76b6vihawBhhEcER7J/yxMrECF3v8TLEr+V7lP/t/qu+C/grAGsgYYRhUABUiD10ywJpCtDV6z/ksLKKKogWJUgXb/RcAAWQjEi/6HG2dhC00YxhTkZOXGEMOCsQoSwAz/AUZL+dIX/BrCAAAAAElFTkSuQmCC)        
</a>
# SatPad

30% ortholinear keyboard built using ergogen v3. 

![rev2](images/rev2-wireless.jpg) 
![front](images/front.jpg) 
![back](images/back.jpg)

## ERGOGEN V3!
I have not updated this project to use Ergogen v4 and am unlikely to do so.


## Features

- 30 key ortholinear split (10 column, 3 row)
- scroll wheel encoder with click
- OLED display

## Sponsored by PCBWay
This project was initially just to learn, but PCBWay reached out and offered to sponsor further development.  They've been awesome - great quality, fast fabrication and great customer service.  I'll definitely be using them for future projects.

<a href="https://www.pcbway.com/project/shareproject/SatPad_rev2_53e17b07.html">Order on PCBWay</a>
## Ergogen
built using my customized fork of ergogen that adds a bunch of footprints.

https://github.com/jasonhazel/ergogen/tree/jasonhazel


## Materials
* 1x ProMicro or equivalent
* 1x SSD1306 OLED Screen (optional, QMK Only)
* 30x 1N4148 SOD-123 Diodes
* 30x Kailh Choc v1
* 30x 1u Kailh Choc Keycaps
* 1x EVQWGD001 Encoder
* 1x C128955 Switch (optional)
* 1x LiPo Battery (optional)

## Firmware
QMK: https://github.com/jasonhazel/qmk_firmware/tree/hazel/satpad

ZMK: https://github.com/jasonhazel/zmk-config/tree/satpad

## Keymap
![Keymap](images/keymap.png)
