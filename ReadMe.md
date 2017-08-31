# VBAP package for Max
[![Build Status](https://travis-ci.org/nwolek/vbap.svg?branch=master)](https://travis-ci.org/nwolek/vbap)
[![Build status](https://ci.appveyor.com/api/projects/status/vn5l7cmal244ti57?svg=true)](https://ci.appveyor.com/project/nwolek/vbap)


Legacy objects for Vector Based Amplitude Panning in Max authored by [Ville Pullki](https://people.aalto.fi/index.html#ville_pulkki) and adapted by [Nathan Wolek](https://github.com/nwolek).

## About

This GitHub project is a [package for Cycling74's Max](https://cycling74.com/2013/03/11/max-6-feature-packages/), versions 6.1 or higher. It provides newly compiled, 64-bit versions of Ville Pullki's objects for vector-based amplitude panning that were originally developed in 1998.

Vector-based amplitude panning is a technique for spatializing sound across multiple loudspeakers. It is flexible enough to define an arbitrary number of speakers in 2D or 3D space. After speaker positions are defined, the user can move a single sound source through the configuration by adjusting its apparent azimuth and elevation.

Additional resources:  
- [AES paper on VBAP](http://lib.tkk.fi/Diss/2001/isbn9512255324/article1.pdf) by Ville Pullki, published originally in 1997 by Journal of the Audio Engineering Society  
- [Legacy website for research group](http://legacy.spa.aalto.fi/research/cat/vbap/) at Helsinki University of Technology  
- Distinct implementation of [VBAP for PD](https://github.com/pierreguillot/vbap) by Pierre Guillot of CICM  
- [3D Sound Primer](http://www.garykendall.net/papers/3-DPrimer1995.pdf) by Gary Kendall, published originally in 1995 by Computer Music Journal 

## Installing

If you have [Git](http://git-scm.com/) installed, you can install via the Terminal using the following commands for Max 7:

	cd ~/Documents/Max\ 7/Packages
	mkdir vbap
	cd vbap
	git clone https://github.com/nwolek/vbap.git
	
For Max 6.1, replace the first line above with the following, and then proceed with the remainder:

	cd ~/Documents/Max/Packages

If you do not have Git installed, you can [download the latest release here](https://github.com/nwolek/vbap/releases). After decompressing the zip archive, the resulting folder can be placed in one of the following folders:

* `~/Documents/Max\ 7/Packages`
* `~/Documents/Max/Packages`

## Bug reporting
If you feel that you have found a bug, please report it via [the Issues section](https://github.com/nwolek/vbap/issues) of this GitHub project site.
