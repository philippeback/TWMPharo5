Making Tiling Window Manager work in Pharo 5.0
=============================================

[Pharo](http://pharo.org)

Tiling Window Manager (TWM) is a window manager for Pharo.

Pharo 5.0 is the next release of Pharo.

This project will make it work nicely in Pharo 5.0 and restore some features that were working in shaky ways in previous versions.

Coding happens on [LiveCodingTV](http://livecoding.tv/philippeback).

TWM base code is on [SmalltalkHub](http://smalltalkhub.com/#!/~LaurentLaffont/TilingWindowManager).

My current code dump is on [SmalltalkHub TWM for Pharo 5](http://smalltalkhub.com/#!/~philippeback/TWM).


To load it from a Playground:

    Gofer it
      url: 'http://smalltalkhub.com/#!/~philippeback/TWM';
      configurationOf: 'TilingWindowManager';
      loadDevelopment.
