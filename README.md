# arduino_irrec
Learning Infrared Remote Controller

Please read the attached LICENSE file prior using the software.

This software is intended to run on 16 MHz Arduino (Arduino Uno R3,
etc).

An infrared LED should be connected to GPIO 2, 3, 4, 5 and 6 in
parallel to source enough current to the LED.  In addition, IR sensor
(e.g. Everlight IRM-3638N3) needs to be hooked appropriately to GPIO
port 7.

When you run the code, it goes into interactive mode.  Type 'h' and CR
to see command help.

To decode receiving IR pattern, use command 'r'.  It shows modulation
patterns and also received command in hex.  To let Arduino remember
the modulation pattern, use command 'p'.  To transmit a command, use
command 't'.

The output of the command 'r' can be used directly to command the
software.  They are displayed with required command 'R' and 'T'.

For your convenience, a Python script to communicate with the software
is also attached.  It is expected to run on Raspberry Pi or etc.

Aug. 30, 2015

## Presentation Material (in Japanese)

Now, the original presentation material is provided [here](http://flogics.com/wp/wp-content/uploads/2020/06/presen_v12_public_shrink-min.pdf).
(The presentation material is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.  Not BSD license.)

Yokoyama, Atsushi

Firmlogics
