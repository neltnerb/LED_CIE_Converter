# LED_CIE_Converter
Allows adding CIE coordinates of any number of LEDs to produce arbitrary mixed colors with as few LEDs as possible.

Written for the Teensy (PJRC.com) with the CIE estimates for colors manually derived from typical color LED datasheet spectra.

Allows an LED to be indicated for "special effects" (such as blacklight) and operated separately.

Includes a color cycler, fader, and some other basic effects to do with the LEDs.

Uses the CIE-LUV colorspace math as best I was able to interpret it. It's not going to be perfect, one thing of particular note is that CIE-LUV red does not appear to be LED red colors so for practical effects where you want "red" to just be the red LED you can add an appropriate offset. The red it calculates is as close as possible to "true CIE red".

I haven't made changes to this since 2015, and don't know how to accept bug fixes (I'm more of a physics and art person) but if you find something and are willing to walk me through it I'm happy to try!
