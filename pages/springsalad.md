---
title: SpringSaLaD Simulator of Langevin Dynamics
layout: default
permalink: springsalad
---

# SpringSaLaD software

SpringSaLaD [software](https://vcell.org/ssalad) is built with a 
GUI supporting model creation, running simulations, and data collection. 
It is available for download for Mac, Unix, and Windows platforms. 

<img src="/images/SpringSaLaD.png" width=400>

SpringSaLaD is:

* a particle-based, spatial stochastic simulator for molecules in 3D
molecules presented as a collection of impenetrable spheres (called “sites”) in 3D linked by stiff springs.

* The sites represent protein binding domains, such as an SH2 domain or a catalytic domain,
each site can be associated with a number of biochemical states, such as “active” or “inactive” for a catalytic domain.
* each site has a separate diffusion
* binding among sites is represented as a formation of a new spring between sites
* supports particle creation, particle decay, association and dissociation, and state transitions.

SpringSaLaD is most suitable for modeling mesoscopic systems, which are far 
too large to be modeled with molecular dynamics but which require more detail 
than obtainable with macroscopic continuum models.  A good example of a system which is best modeled with SpringSaLaD is ligand-mediated receptor clustering, where coarse-grained particle-level interactions are required but atom-level information is not of interest. In general, SpringSaLaD is best used 
to model mesoscopic particles (diameters of 1 – 10 nm, which could represent a functional 
protein domain), moderately sized systems (10 – 10,000 particles), and times scales 
on the order of 1 second, but no actual restriction is set on size or scale of the 
simulated system.

<img src="/images/R.png" width=150><img src="/images/L.png" width=150><img src="/images/RL.png" width=150>


