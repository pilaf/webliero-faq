# WebLiero Unofficial Changelog

## July 11, 2020

* Fixed a memory leak that caused servers to degrade over time, causing lag spikes (especially upon new players joining).

## June 3, 2020

* Added PNG maps support. PNG maps have no size limitation (unlike .lev maps which are limited to a fixed size), however they are still constrained by the Liero palette. PNG maps must be in indexed 256-color mode, although the palette in the PNG file will be replaced with Liero's in-game.

## May 30, 2020

* Added background shadows for worms and other game objects (i.e. particles).
* Added blinking white dot to out-of-screen worm indicators (to improve visibility when the worm color is close to the background color).
* Added flag indicator for when flag goes out of screen in Hold the Flag mode.
* Flag now resets position if not grabbed for about 15 seconds (to prevent it getting stuck at unreachable places).

## August 10, 2019

* WebLiero officially released ([Twitter announcement](https://twitter.com/lieroofficial/status/1160174180337442817))
