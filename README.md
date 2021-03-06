# PicoFuzz

---

*For more DIY pedal fun (e.g. [a 3PDT board version](https://shop.mas-effects.com/products/stompfuzz)  of this), visit the [MAS Effects](https://mas-effects.com) page.*

---

The tiniest fuzz, because... why not?

This is a fun and practical guitar pedal, and a great opportunity to practice surface mount (SMD) soldering (and do so with nothing but your regular soldering iron).

### How to get it

You can either download the gerber files from this repo, or [buy it on my store here](https://shop.mas-effects.com/products/3-picofuzz-pcbs).

## Intro

This is a bazz fuss circuit, with endless possibilities to try. 

I recommend experimenting with component values. e.g. see these writeups for some ideas to get started

* [tonefiend project](https://www.tonefiend.com/wp-content/uploads/DIY-Club-Project-2-v02.pdf)
* [home-wrecker.com writeup](http://home-wrecker.com/bazz.html)

## Pics and Wiring Diagram

![picofuzz](/picofuzz.jpg)

![picofuzz wiring](/picofuzz-wiring.png)

## Assembly Tips 

You can solder SMD components with a regular soldering iron, and no special tools or equipment. It doesn't take a lot of practice, and this board is great for it.

[This SMD soldering video](https://www.youtube.com/watch?v=P5XwpNuIvf0) goes through the basic process.

Here are some tips:

* **Soldering steps**
  * Pre-tin one pad on the PCB
  * In your non-dominant hand: Place and hold the component with tweezers
  * With your dominant hand: Heat the component and the pad simultaneously with the soldering iron. Solder should flow up onto the component.
  * You no longer need the tweezers.
  * Go to the other side of the component and apply heat to the component and pad, then touch a tiny amount of solder to it.
  * Optionally, if necessary, go back to the first pad and add a bit more solder.
* **Soldering iron tip size and shape**: It may seem intuitive to use a tiny tip on your iron, but this will probably make the job more difficult since it will be harder to apply even heat to both the component and pad. Instead, use a regular conical pencil-type of tip.

## Schematic

NOTE: Resistors and capacitors are 0805 packages.

You can and should substitute other values for all the components. But these are decent starting points.

![picofuzz schematic](/picofuzz-schematic.png)

## Combinations to try

TODO: This should be filled in and fleshed out further

### Q1 and R1

* MMBTA14LT1G + 100k-510k
* MMBT6427LT1G  + ?
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
