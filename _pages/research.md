---
title: "Research"
permalink: /research/
author_profile: true
---

## Deep learning for more accurate sea surface height mapping 
*2021-present, with [Georgy Manucharyan](https://deep.ocean.washington.edu/) & [Patrice Klein](https://www.gps.caltech.edu/people/jean-patrice-m-patrice-klein)*

*[Global mapping GRL paper](https://doi.org/10.1029/2024GL110059)*
*[Gulf Stream proof-of-concept JAMES paper](https://doi.org/10.1029/2022MS003589)* 

![neural network](/images/figure1.png)

Gridded sea surface height (SSH) maps are widely used in oceanography for estimating surface ocean currents. However, SSH is typically only measured along narrow, widely-spaced tracks by satellite-borne nadir radar altimeters. Producing a gridded SSH product therefore requires significant spatiotemporal interpolation, which has traditionally been done using optimal interpolation (as in the widely-used [DUACS](https://duacs.cls.fr/) product). However, in regions with energetic mesoscale ocean turbulence the optimal interpolation method tends to smooth out the 2D SSH signal in both space and time. 

Motivated by [earlier work](https://doi.org/10.1029/2019MS001965) showing that a deep learning neural network could be trained to accurately interpolate SSH in an idealised ocean turbulence model, we're attempting to develop a deep learning method for more accurately mapping SSH in energetic ocean regions.

A deep learning approach allows us to utilise co-located observations of sea surface temperature (SST, a quantity with a close dynamical relationship to SSH) to improve the SSH mapping. Using SST observations to improve SSH mapping has long been [proposed]( https://doi.org/10.1029/2006GL027801), but is challenging to achieve in a hand-coded algorithm, unlike when using a deep learning approach.

Our [paper](https://doi.org/10.31223/X50Q0N) presents our method and demonstrates that it can improve both the accuracy and effective resolution of gridded SSH maps in the Gulf Stream Extension. We've now scaled up our method to produce new state-of-the-art global SSH maps that better resolve mesoscale ocean dynamics, see our latest [pre-print](https://doi.org/10.31223/X5W676) for more details.

## Mesoscale-submesoscale ocean scale interactions 
*2023-present, with [Georgy Manucharyan](https://deep.ocean.washington.edu/) & [Patrice Klein](https://www.gps.caltech.edu/people/jean-patrice-m-patrice-klein)*

*[Global mapping pre-print](https://doi.org/10.31223/X5W676)*

![cascade](/images/ke_flux.png)

Mesoscale eddies (ocean vortices ~100-1000km across) account for the majority of the ocean's kinetic energy and strongly impact global climate through their strong lateral transport of heat, salt, and other tracers. Submesoscale turbulence (eddies and filaments ~1-10 km across) is another class of oceanic motions of smaller horizontal scale which have their own distinct dynamics that can induce strong vertical velocities with significant net vertical transports of heat, carbon, and nutrients. Since submesoscale turbulence is as yet unresolved in global climate models, quantifying its impact on the larger-scale circulation is crucial for understanding the ocean's role in global climate. Submesoscale processes can act as both a source and sink for mesoscale kinetic energy and submesoscale dynamics is strongly seasonal, mesoscale-submesoscale scale interactions are thus a rich and complex area of study. In my research, I aim to better characterise these interactions using satellite observations.

Geostrophic turbulence theories predict that non-linear eddy-eddy interactions transfer kinetic energy upscale (from small scales to large). Submesoscale eddies are known to preferentially form in the winter-time (through mixed layer instability) and mesoscale kinetic energy is observed to peak in the summer-time across much of the ocean. It has therefore been hypothesised that this summer-time peak in mesoscale kinetic energy is driven by an upscale cascade from submesoscale eddies. Using our new AI-derived high-resolution global SSH maps, we [showed](https://doi.org/10.31223/X5W676) that satellite altimeter observations in the subtropics are broadly consistent with this picture since they show a strong upscale cascade in the small mesoscale range that peaks in the late winter/early spring. This result stands in contrast to studies that used the existing lower-resolution global SSH product.

## Tidal circularisation of binary stars 
*2020-2021, with [Caroline Terquem](https://www.physics.ox.ac.uk/our-people/terquem)*

*[Paper](https://doi.org/10.1093/mnras/stab2322)*

![p_circ](/images/p_circ_fig.png)

During the research for my MPhys project I studied the interaction between convection and tides inside binary stars. Binary stars are pairs of companion stars locked in a mutual orbit. In the same way as the Moon causes tides in the Earth's oceans, binary stars cause tides on one another. It has long been observed that close-orbitting binary stars have mostly circular orbits, while wider-orbitting binaries can have more elliptical orbits. It has long been thought that this apparent circularisation process is caused by orbital energy being dissipated by tidal friction inside the stars, though the exact details of this tidal friction mechanism are still an area of active research. 

Using a new [theory](https://doi.org/10.1093/mnras/stab224) for how tidal energy can be dissipated by the interaction between tides and convection inside stars, I calculated the expected circularisation time-scales for a binary star system containing two Sun-like stars. By explicitly including the time-evolving internal structure of the stars (estimated using a [numerical model](https://docs.mesastar.org/en/release-r22.11.1/) of stellar evolution), we found circularisation time-scales in much closer accordance with observed values than previous theories (see the above figure from my unpublished MPhys dissertation - a similar figure is included in our MNRAS [paper](https://doi.org/10.1093/mnras/stab2322)).
