# A Golang library to control the Raspberry Pi's GPIO interface #

This is a library for controlling the Raspberry Pi's GPIO pins from Go programs, using the /sys filesystem instead of direct device file access.

## How It Works ##

TBD

## Acknowledgements ##

This project draws inspiration and borrows heavily from the work done by @alexellis on [Docker on Raspberry Pis](http://blog.alexellis.io/visiting-pimoroni/) and his [Blinkt Go libraries](https://github.com/alexellis/blinkt_go), themselves based on work by @gamaral for using the `/sys/` fs interface [instead of special libraries or elevated privileges](https://guillermoamaral.com/read/rpi-gpio-c-sysfs/) to `/dev/mem` on the Raspberry Pi.

## Requirements ##

A Raspberry Pi computer. It should work in all models but it's only been tested on the Raspberry Pi 3.

## Usage ##

TBD

## License ##

This library is made available under an MIT-style License. See [LICENSE](./LICENSE).