# PicoFuzz

The tiniest fuzz, because... why not?

Resistors and capacitors are 0805 packages.

![picofuzz wiring](/picofuzz-wiring.png)

## Intro

This is a bazz fuss circuit, with endless possibilities to try. 

I recommend experimenting with component values. e.g. see these writeups for some ideas to get started

* [tonefiend project](https://www.tonefiend.com/wp-content/uploads/DIY-Club-Project-2-v02.pdf)
* [home-wrecker.com writeup](http://home-wrecker.com/bazz.html)

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

## Schematic

You can and should substitute other values for all the components. But these are decent starting points.

[picofuzz schematic](/picofuzz-schematic.png)

## Optional add-ons:

* diode for polarity protection
* filter power supply for noise. e.g. 22uF cap between +9V and GND
* LED: and optionally anti-pop on LED
* a resistor from the input tip to ground to help limit switch popping
