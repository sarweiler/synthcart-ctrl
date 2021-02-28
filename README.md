# Synthcart Ctrl

Synthcart Ctrl is a controller for the Atari 2600 synthesizer [Synthcart](http://www.qotile.net/synth.html) by Paul Slocum. It's basically two Atari keyboard controller circuits on a single PCB.

![Synthcart Ctrl](images/synthcart-ctrl.jpg)

## Building Synthcart Ctrl

Building a Synthcart Ctrl is a very easy and beginner-friendly soldering project.

### PCB

Download the [synthcart-ctrl-gerbers.zip](https://github.com/sarweiler/synthcart-ctrl/releases/latest/download/synthcart-ctrl-gerbers.zip) file for the latest release, upload the zip archive to a PCB manufacturer of your choice, and order a PCB. Usually the default settings for the PCBs are okay – just choose a color for the solder mask that you like, if you dont want the standard PCB-green.

### Parts

* Four 4.7kOhm resistors.
* 24 Cherry MX switches of your choice, preferably of the PCB-mount variant (with fixation pins, [these, for example](https://www.mouser.com/ProductDetail/540-MX1A-11NW)). Non-PCB-mount switches (frame mount, without fixation pins) will work, too, but you will have to be careful to align them correctly when soldering.
* Two female DB9 connectors of the PCB-mount variant with mounting pins ([these](https://www.mouser.com/ProductDetail/571-2311765-1), [these](https://www.reichelt.de/d-sub-buchse-9-polig-gewinkelt-rm-9-4-gedr-d-sub-bu-09gwc-p113921.html), or any connector with similar measurements will work).
* 24 Cherry MX compatible keycaps of your choice. (I used [these](https://www.aliexpress.com/item/32987364794.html?spm=a2g0s.9042311.0.0.27424c4dBs286T) in the "blank" variant.)
* Two DB9 extension cables for connecting the controller to the Atari.
* 4 rubber feet

### Soldering

* Start by soldering the four 4.7k resistors.
* Solder the two female DB9 connectors.
* Solder all 24 Cherry MX switches. If you're using non-PCB-mount switches be careful to align them correctly.
* Install your keycaps on the switches.
* Add the rubber feet to the bottom of the PCB to avoid shorts when using the controller on conductive surfaces.
* Done!

## Using Synthcart Ctrl

Using the controller is pretty straight forward: Connect the left port of your controller to the left joystick port on the Atari and the right port to the right joystick port on the Atari using two DB9 extension cables.

Use the two sides of the controller like you would use two Atari keyboard controllers to control Synthcart.

For information on how to use Synthcart, check out the [Synthcart](http://www.qotile.net/synth.html) manual.

## Disclaimer

Build and use Synthcart Ctrl at your own risk. I cannot be held responsible for damage caused to your devices, yourself or others.


![pcb artwork](images/apc.png)

## License

This work is licensed under [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).

[![CC-BY-SA](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)