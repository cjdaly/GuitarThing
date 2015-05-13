## GuitarThing

GuitarThing is an Internet of Things inspired artwork framed on a 20x20 inch canvas.

![GuitarThing](https://github.com/cjdaly/GuitarThing/wiki/images/GuitarThing.jpg)

Embedded in GuitarThing is a Linux computer with several audio devices.

### Technical Specifications

* BeagleBone Black [model A6](http://elinux.org/Beagleboard:BeagleBoneBlack) running Ubuntu Linux.
* Audio peripheral devices:
  * [MP3 Trigger](https://www.sparkfun.com/products/11029) for playing songs or sound effects.
  * [Emic2](https://www.sparkfun.com/products/11711) for speaking text.
  * [Shamp Model 1](https://github.com/cjdaly/shamp) for mixing MP3 Trigger and Emic2 audio.
  * USB powered speakers (not visible, behind canvas) to amplify Shamp output.

In low light conditions, LEDs on several of the parts cast light onto the canvas.

![GuitarThing lights](https://github.com/cjdaly/GuitarThing/wiki/images/GuitarThing-lights.jpg)

* Emic2 (upper right) casts a green glow when idling (red when speaking).
* MP3 Trigger (center) power light casts a red glow.
* BeagleBone Black Ubuntu distribution ties Linux heartbeat to blue LED.

### Wiki topics

* Details of the [concept and construction](https://github.com/cjdaly/GuitarThing/wiki/Concept-and-Construction).
* Controlling the peripheral [audio devices](https://github.com/cjdaly/GuitarThing/wiki/Audio-Device-Usage).

