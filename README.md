# Mod Player for the Sega Mega CD

## Description

This project shows an example of how the Sega Mega CD can be used to play MOD files via the Sega Mega CD's PCM RAM.  The code is based upon Ami-PlayMOD by Massimiliano Scarano.

A couple of important pointers:
* Each sample must be under 128KiB
* If the total size of all samples is larger than 64KiB.  The biggest sample is halved and the base note value adjusted to play at the correct pitch.  This is repeated until all samples fit into 64KiB.  This means overall larger samples will deteriorate in quality.

## "Mod Player for the Sega Mega CD" Credits
* Programming : Chilly Willy
* Base Docker Code : Victor Luchits
* Additional Docker Code for compatibility : Matt B (Matteusbeus)

## "Ami-PlayMOD" Credits
* Programming : Massimiliano Scarano

## 

## Links
https://aminet.net/package/mus/play/Ami-PlayMOD_V1_0.lha

https://github.com/viciious/d32xr/tree/master/.devcontainer

## License
All original code is available under the MIT license.