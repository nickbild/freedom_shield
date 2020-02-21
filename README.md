# Freedom Shield

<p align="center">
<img src="https://raw.githubusercontent.com/nickbild/freedom_shield/master/media/freedom_shield.gif">
</p>

The freedom of assembly is widely considered to be a basic human right and is codified in documents such as the First Amendment to the US Constitution and the Universal Declaration of Human Rights.  However, there are many places in the world where this right is not respected.

We are living in a time where surveillance cameras, with the ability to uniquely identify individuals through machine learning algorithms, are exceedingly common.  Such cameras can be used to deter people from exercising their rights.

Freedom Shield was developed to protect the rights of individuals to peaceably assemble and petition their government while:

- Blocking their face from surveillance cameras to prevent identification.
- Being invisible to onlookers, so as to not draw attention from state police forces in the way a mask would.

The device described here can be built for a few dollars in parts, and with little skill required, making it widely accessible.

## How it Works

Freedom Shield uses 940nm infrared (IR) LEDs embedded in clothing (e.g. hats, glasses, headphones, etc.) to overwhelm the photodiodes in cameras sensitive to IR radiation.  Many surveillance cameras are sensitive to IR radiation to enable night vision via detection of reflected or emitted IR sources.  However, IR is outside of the spectrum of radiation visible to humans, which extends to ~740nm, rendering the light invisible.

## Media

YouTube Video:
https://www.youtube.com/watch?v=mRwF_LFY0IU

## Schematic

Note: Voltage and resistor value are dependent on choice of LEDs (in particular, the forward voltage and forward current).

![Schematic](https://raw.githubusercontent.com/nickbild/freedom_shield/master/diagram/schematic.jpg)

## Bill of Materials

- 940nm LEDs
- Resistors of an appropriate value for chosen LEDs and voltage source
- Miscellaneous wire
- Battery pack
- Articles of clothing to embed LEDs (hat, glasses)

## Future Direction

Rather than large through-hole LEDs, I'd like to use smaller SMD LEDs, which can then be fully embedded in the fabric.  This would render the device fully invisible.

## About the Author

[Nick A. Bild, MS](https://nickbild79.firebaseapp.com/#!/)
