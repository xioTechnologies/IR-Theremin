IR-Theremin
===========
IR Theremin is a simple application that uses [x-OSC](http://www.x-io.co.uk/x-osc/) and a pair of [infrared proximity sensors](https://www.sparkfun.com/products/242) from [sparkfun](https://www.sparkfun.com) to recreate a [Theremin](https://en.wikipedia.org/wiki/Theremin), one of the earliest electronic musical instruments. It also shows how to interface to [x-OSC](http://www.x-io.co.uk/x-osc/) using [Pure Data](http://puredata.info/) (Pd-extended) and [Max/MSP](http://cycling74.com/products/max/). 

x-OSC settings:

1. analogue sample rate: 100 Hz
2. inputs 1 and 2 set to analogue

Wiring:

<img src="https://raw.github.com/xioTechnologies/IR-Theremin/master/Wiring%20Diagram.png" alt="IR Theremin Wiring" style="width: 600px;"/>


<!--The demo video begins with the full process of switching on the x-OSC, connecting to its ad hock network, configuring it's inputs and connecting the IR sensors before ending with a short demonstration.-->

The Pd patch requires [Pd-extended](http://puredata.info/downloads).