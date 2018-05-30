# Double Agent at MOD.

<img width=100% src="mod-double-agent.jpg" />

Can you teach an algorithm to dance?

Double Agent is an interactive dance piece built by [Simon Biggs](https://github.com/SimonBiggsUK) for an exhibit at MOD. from May - October 2018.

The exhibit is in two parts - a pre-trained Machine Learning algorithm that generates artificial human skeletons based on hundreds of hours of training watching professional dancers.

The second part is a live interactive display, using a Kinect 2 sensor to detect live skeletons of people dancing in front of it.

Read more: [mod.org.au/double-agent](https://mod.org.au/exhibits/double-agent/) 

Or visit [Double Agent at MOD.](https://mod.org.au/visit/getting-here/).

## Software

The software was written by Simon Biggs using the [Processing.org](https://processing.org) framework.

There are three Processing sketches to run Double Agent.

1. [Kinect2UDP](Kinect2UDP) - sensor to detect live skeletons, and a UDP server to send the skeleton data to another computer to display the data.
2. DoubleAgent 1 - projection app showing the machine learning data.
3. DoubleAgent 2 - projection app showing the live data.

**TODO**: Add double agent projects as [sub-modules](https://blog.github.com/2016-02-01-working-with-submodules/)

There are also some third party libraries used that aren’t included in this repository, below are instructions to install them:

* **TODO**: include instructions.

## Hardware

Simon Loffler designed a plinth to house the Kinect 2 sensor and micro-pc to run the Kinect 2 UDP processing sketch.

* [kinect-plinth](kinect-plinth) has the [SketchUp](https://www.sketchup.com) files to build your own out of 10mm MDF.
* Install SketchUp, and then open `MOD_Double_Agent_Plinth.skp`.

## Credits

* Artist & Programmer: [Simon Biggs](http://littlepig.org.uk/)
* Machine Learning developer: Samya Bagchi
* Choreography: Sue Hawksley and Tammy Arjona
* Project management: [MOD.](https://mod.org.au) ([Simon Loffler](https://github.com/sighmon))

## License

Released under an [MIT License](LICENSE).

Copyright (c) 2018 [MOD.](https://mod.org.au)