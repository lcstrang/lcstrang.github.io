---
layout: post
title: Plerion model of the X-ray plateau in short gamma-ray bursts
description: >
  A simple model to describe X-ray plateaux as observed following some short Gamma-Ray Bursts
sitemap: false
hide_description: false
hide_last_modified: true
author: true
image: 
    path: /assets/img/papers/crab.jpg
    srcset:
        2400w: /assets/img/papers/crab.jpg
        1200w: /assets/img/papers/crab@0,5x.jpg 
        600w:  /assets/img/papers/crab@0,25x.jpg 
        300w:  /assets/img/papers/crab@0,125x.jpg 

categories: [papers]
tags: [grbs, phd] 
date: 2019-07-02
---

Central-engine models for sGRBs have a lot of similarities to early models of young supernova remnants (such as the Crab nebula, pictured). 
How much of our knowledge of supernova remnants can we leverage to explain observations of sGRBs and their afterglows?


## Citation
**Strang, L. C.**, and A. Melatos. "Plerion model of the X-ray plateau in short gamma-ray bursts." *Monthly Notices of the Royal Astronomical Society* 487.4 (2019): 5010-5018.
arxiv: [1906.02877](https://arxiv.org/abs/1906.02877)

## Abstract

Many short gamma-ray bursts (sGRBs) exhibit a prolonged plateau in the X-ray light curve following the main burst. It is shown that an X-ray plateau at the observed luminosity emerges naturally from a plerion-like model of the sGRB remnant, in which the magnetized, relativistic wind of a millisecond magnetar injects shock-accelerated electrons into a cavity confined by the sGRB blast wave. A geometry-dependent fraction of the plerionic radiation is also intercepted and reprocessed by the optically thick merger ejecta. The relative contributions of the plerion and ejecta to the composite X-ray light curve are estimated approximately with the aid of established ejecta models. The plerionic component of the electron energy spectrum is evolved under the action of time-dependent, power-law injection and adiabatic and synchrotron cooling in order to calculate the X-ray light curve analytically. The model yields an anti-correlation between the luminosity and duration of the plateau as well as a sudden cut-off in the X-ray flux, if the decelerating magnetar collapses to form a black hole. Both features are broadly consistent with the data and can be related to the surface magnetic field of the magnetar and its angular velocity at birth. The analogy with core-collapse supernova remnants is discussed briefly. 

## Overview
##### The observations

<figure>
<img src="/assets/img/papers/GRB130603B_data_lc.png" alt="Observed X-ray flux for GRB130603B" style="float:right;width:50%"/>
<figcaption style="text-align:right;position:static;float:right;width:51%"><b>Figure 1.1:</b> 0.3 keV -- 10 keV observations of GRB130603B by <a href="https://www.swift.ac.uk/xrt_curves/"><i>Swift</i></a>. </figcaption>
</figure> 


sGRBs are extremely bright, transient sources of light which last only a couple of seconds in the gamma-ray spectrum. 
Many sGRBs display an extended afterglow at longer wavelengths. 
In the case of X-rays, the afterglow sometimes takes the shape of a `plateau' (Fig. 1).
A typical X-ray plateau has three components: an initial decline, a plateau phase lasting from 10 s to $$10^5$$ s, and a final decline. 
The last two phases are shown in Figure 1. for GRB130603B.
The source of the plateau is widely debated in the community for several years, but no consensus has yet been reached.



##### The physics

One popular class of models proposes that the prolonged emission in the X-ray band is evidence of ongoing energy injection from a central engine. 
The most likely culprit is a millisecond magnetar: a highly magnetized, rapidly rotating neutron star.
In this scenario, the rotational energy of the star is extracted via magnetic dipole braking and becomes the observed X-ray emission. 
At a high level, this is similar to early models of young pulsar wind nebulae, in particular the Crab nebula (Fig. 2.1).
My PhD supervisor, Prof. Andrew Melatos, proposed the mechanism driving X-ray production following sGRBs may be similar to that driving X-ray production in pulsar wind nebulae.

<figure>
<img src="/assets/img/papers/crab.jpg" alt="Observed X-ray flux for GRB130603B" style="width:60%"/>
<figcaption> <b>Fig. 2.1:</b> Composite image of the Crab nebula combining data from Hubble (optical wavelengths; red) and Chandra (X-rays; blue). Image via <a href="https://en.wikipedia.org/wiki/Crab_Nebula">Wikipedia</a>.</figcaption>
</figure> 

What, then, is the physics?
We assume that the merger leaves behind a rapidly rotating neutron star, which brakes electromagnetically as it emits a magnetized leptonic wind.
As the pulsar spins down, its rotational energy is converted into a mixture of mechanical and electromagnetic energy flux.
The interaction of the wind with the surrounding environment launches a reverse shock back into the wind, creating a 'bubble' of electrons just behind the shock. 
In the full [paper](https://arxiv.org/abs/1906.02877), we explore the evolution of the electron distribution function *N(E,t)* under the effects of synchrotron radiation, adiabatic expansion, and the injection of new electrons as the reverse shock propagates into the wind. 
We solve the partial differential equation governing the system and use *N(E,t)* to infer the synchrotron luminosity and spectrum as a function of time.


##### The data

<figure>
<img src="/assets/img/papers/GRB130603B_lc.png" alt="Observed X-ray flux for GRB130603B" style="float:right;width:50%"/>
<figcaption style="text-align:right;position:static;float:right;width:51%"><b>Figure 3.1:</b> 0.3 keV -- 10 keV observations of GRB130603B by <a href="https://www.swift.ac.uk/xrt_curves/"><i>Swift</i></a> (black crosses) and a sample light curve produced by our model (blue curve). </figcaption>
</figure> 


The goal of this work is to see if this simple model summarized above can produce light-curves similar to those observed following sGRBs.
The answer, as seen in Figure 3.1, is yes. 
The black crosses are observations of GRB130603B taken by the Neils Gehrels <a href="https://www.swift.ac.uk/xrt_curves/"><i>Swift</i></a> telescope, identical to Figure 1.1.
The blue curve is a sample light curve produced by our model.
Crucially, the blue curve is not a best-fit curve, but simply a sample curve produced using hand-chosen millisecond magnetar parameters. 
This is as much as we could reasonably expect from this simple model, but in the full [paper](https://arxiv.org/abs/1906.02877) we manage to reproduce additional observational features in the light curves.
In [Strang et al (2021)](SMSL21), we go a step further, using the spectra of six sGRBs to infer the parameters of the central engine driving the emission. 



##### Take-home message

If a millisecond magnetar survives the sGRB, the relativistic outflow can be modelled using a simple model similar to early models of young supernova remnants. 
However, a more mature model is needed to see if this idea is competitive with established afterglow models in the field. 

## Acknowledgements

All scientific acknowledgements can be found in the reference section of the paper.
The following additional resources were used on this page:

* Fig 2.1: Composite image of the Crab nebula combining data from Hubble (optical wavelengths; red) and Chandra (X-rays; blue). Image via <a href="https://en.wikipedia.org/wiki/Crab_Nebula">Wikipedia</a> 
