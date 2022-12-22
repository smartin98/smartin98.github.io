---
title: "Research"
permalink: /research/
author_profile: true
---

## Deep learning for more accurate sea surface height mapping 
*2021-present, with [Georgy Manucharyan](https://deep.ocean.washington.edu/) & [Patrice Klein](https://www.gps.caltech.edu/people/jean-patrice-m-patrice-klein)*

*[Pre-print](https://doi.org/10.31223/X50Q0N)* 

![neural network](/images/ConvLSTM_SSH-SST.jpg)

Gridded sea surface height (SSH) maps are widely used in oceanography for estimating surface ocean currents. However, SSH is typically only measured along narrow, widely-spaced tracks by satellite-borne nadir radar altimeters. Producing a gridded SSH product therefore requires significant spatiotemporal interpolation, which has traditionally been done using optimal interpolation (as in the widely-used [DUACS](https://duacs.cls.fr/) product). However, in regions with energetic mesoscale ocean turbulence the optimal interpolation method tends to smooth out the 2D SSH signal in both space and time. 

Motivated by [earlier work](https://doi.org/10.1029/2019MS001965) showing that a deep learning neural network could be trained to accurately interpolate SSH in an idealised ocean turbulence model, we're attempting to develop a deep learning method for more accurately mapping SSH in energetic ocean regions.

A deep learning approach allows us to utilise co-located observations of sea surface temperature (SST, a quantity with a close dynamical relationship to SSH) to improve the SSH mapping. Using SST observations to improve SSH mapping has long been [proposed]( https://doi.org/10.1029/2006GL027801), but is challenging to achieve in a hand-coded algorithm, unlike when using a deep learning approach.

Our [pre-print](https://doi.org/10.31223/X50Q0N) (submitted to JAMES in Dec. 2022) presents our method and demonstrates that it can improve both the accuracy and effective resolution of gridded SSH maps in the Gulf Stream Extension. We're now working on scaling up and refining our method to produce an improved global SSH product.


## Tidal circularisation of binary stars 
*2020-2021, with [Caroline Terquem](https://www.physics.ox.ac.uk/our-people/terquem)*

*[Paper](https://doi.org/10.1093/mnras/stab2322)*


![p_circ](/images/p_circ_fig.png)

During the research for my MPhys project I studied the interaction between convection and tides inside binary stars. Binary stars are pairs of companion stars locked in a mutual orbit. In the same way as the Moon causes tides in the Earth's oceans, binary stars cause tides on one another. It has long been observed that close-orbitting binary stars have mostly circular orbits, while wider-orbitting binaries can have more elliptical orbits. It has long been thought that this apparent circularisation process is caused by orbital energy being dissipated by tidal friction inside the stars, though the exact details of this tidal friction mechanism are still an area of active research. 

Using a new [theory](https://doi.org/10.1093/mnras/stab224) for how tidal energy can be dissipated by the interaction between tides and convection inside stars, I calculated the expected circularisation time-scales for a binary star system containing two Sun-like stars. By explicitly including the time-evolving internal structure of the stars (estimated using a [numerical model](https://docs.mesastar.org/en/release-r22.11.1/) of stellar evolution), we found circularisation time-scales in much closer accordance with observed values than previous theories (see the above figure from my unpublished MPhys dissertation - a similar figure is included in the [paper](https://doi.org/10.1093/mnras/stab2322) we published).