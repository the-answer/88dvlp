---
layout: blog
title: First Post
---
![The simulated stars and galaxies from my DLS simulation I created during my 2006 physics REU.](http://placehold.it/640x480)


During the summer of 2006, I participated in a [physics REU at UC
Davis](http://london.ucdavis.edu/~reu/REU06/reu06.html). I worked
for [Tony
Tyson](http://www.physics.ucdavis.edu/people/faculty/faculty_profiles/anthony_tyson.html)
in the [UC Davis cosmology
group](http://www.physics.ucdavis.edu/Cosmology/universe.html).
Tony Tyson worked on the [Deep Lens
Survey](http://dls.physics.ucdavis.edu/) and is director of the
upcoming [Large Synoptic Survey Telescope](http://www.lsst.org/).
These experiments use [weak gravitational
lensing](http://en.wikipedia.org/wiki/Weak_gravitational_lensing)
to infer the distribution of dark matter in the universe.



During the REU, I helped build a computer simulation of the DLS to
quantify possible sources of systematic error. The simulation
realistically models the density of stars and galaxies in the
universe with realistic energy distributions. It allows the galaxies
to be distorted by an input dark matter distribution and it
realistically simulates the atmospheric point spread function and
atmospheric noise. It separately simulates the 8 CCD chips that
make up the detector and it simulates the astronomical process of
dithering where multiple exposures at slight offsets are coadded
together. For increased efficiency, I wrote the simulation so that
it could be run in parallel on the computer cluster at Davis. Using
the simulated data, I measured the dark matter signal in the simulated
data and compared it to the signal in the Monte Carlo distribution.
