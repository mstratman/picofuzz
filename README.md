# PicoFuzz

The tiniest fuzz, because... why not?

This is a fun and practical guitar pedal, and a great opportunity to practice surface mount (SMD) soldering (and do so with nothing but your regular soldering iron).

### How to get it

You can either download the gerber files from this repo, or [buy it on my store here](https://mas-effects.square.site/product/10-picofuzz-pcbs/23?cp=true&sa=false&sbp=false&q=false&category_id=7).

### Pics and Wiring Diagram

![picofuzz](/picofuzz.jpg)

![picofuzz wiring](/picofuzz-wiring.png)

## Intro

This is a bazz fuss circuit, with endless possibilities to try. 

I recommend experimenting with component values. e.g. see these writeups for some ideas to get started

* [tonefiend project](https://www.tonefiend.com/wp-content/uploads/DIY-Club-Project-2-v02.pdf)
* [home-wrecker.com writeup](http://home-wrecker.com/bazz.html)

## Schematic

NOTE: Resistors and capacitors are 0805 packages.

You can and should substitute other values for all the components. But these are decent starting points.

![picofuzz schematic](/picofuzz-schematic.png)

## Combinations to try

TODO: This should be filled in and fleshed out further

### Q1 and R1

* MMBTA14LT1G + ...
* MMBT6427LT1G  + 10k
* MMBF5457 + ...
* MMBT3904VL  + 510k
* MMBT5088LT1G + 100k


### D1

* 1N914BWS
* BAT46JFILM

## Buzz Box

Chain two together, with a different diode on the second, e.g. BAT46

## Optional add-ons:

* diode for polarity protection
* filter power supply for noise. e.g. 22uF cap between +9V and GND
* LED: and optionally anti-pop on LED
* a resistor from the input tip to ground to help limit switch popping
