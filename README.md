IR-Theremin
===========
IR Theremin is an open source application that uses [x-OSC](http://www.x-io.co.uk/x-osc/) and a pair of [infrared proximity sensors](https://www.sparkfun.com/products/242) from [sparkfun](https://www.sparkfun.com) to recreate a [Theremin](https://en.wikipedia.org/wiki/Theremin), one of the earliest electronic musical instruments. It also acts as a neat example application demonstrating how to interface to [x-OSC](http://www.x-io.co.uk/x-osc/) using the [Pure Data](http://puredata.info/) (Pd-extended) and the [Max/MSP](http://cycling74.com/products/max/) environments. 

The patch controls the frequency and amplitude of an oscillator using two of [x-OSC](http://www.x-io.co.uk/x-osc/)'s analogue inputs. 

<!--The demo video begins with the full process of switching on the x-OSC, connecting to its ad hock network, configuring it's inputs and connecting the IR sensors before ending with a short demonstration.-->

The Pd patch requires [Pd-extended](http://puredata.info/downloads) for the OSC computable objects.