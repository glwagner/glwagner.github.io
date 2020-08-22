---
title: A few things I work on
header:
  image: /assets/images/blueoffice-2.jpg
permalink: /projects/
---

Have questions about my work? Email me at
`gregory.leclaire.wagner@gmail.com`. 
See my [github] for real-time updates on my software projects.

### Turbulent surface boundary layers

I am developing models for turbulence in the ocean's
surface boundary layer with 'optimized' and uncertainty-quantified
parameters. 
This work is part of the [CliMa] project.

I presented this poster at Ocean Sciences 2020 in San Diego:

![OSM20](/assets/figures/ocean_sciences_2020_poster.png)

The poster shows some recent progress I've made comparing different
one-dimensional models for turbulence near the surface of the ocean to 
high-fidelity numerical simulations. We come to the conclusion that
one model outperforms another in the narrow context we've considered so
far, but there's a lot of work left to do.

### [Oceananigans.jl]

In the course of my work on turbulent boundary layers, I run a lot
of large eddy simulations using [Oceananigans.jl]. 
[Oceananigans.jl] is a fast and friendly code for simulating the motion
of fluids that I'm helping to develop.
[Oceananigans.jl] is written in the Julia programming 
language and runs on Graphics Processing Units.

### Surface gravity waves and turbulence

Frothing, whitecapping, undulating surface waves are the top of the
ocean surface boundary layer. I work a bit on the interactions between
surface waves and boundary layer turbulence.

The image below depicts turbulence simulated by
[Oceananigans.jl]. The image shows the turbulent vertical velocity field
that develops following the growth of a surface wave field with 
a wave length of one hundred meters over four hours.

![Forced growth](/assets/figures/forced_growth.png)

Information about how to produce this image can be found
[on github](https://github.com/glwagner/WaveTransmittedTurbulence.jl),
or in [our paper's preprint](https://glwagner.github.io/assets/pdf/near-inertial-waves-turbulence-growth-swell-preprint.pdf).

### Squeeze dispersion

Squeeze dispersion is a phenomenon by which the dispersion of tracers
is enhanced in the presence of fluctuating strain. 

The image below illustrates two layers of fluid that are colored green
and blue and on which a tracer 'c' has different concentrations.
Due to this difference in tracer concentration, the tracer 'fluxes'
across the fluid between the two layers at the rate 'F'.

![Squeezing][/assets/figures/squeezing.pdf]

Because the flux 'F' is inversely proportional the the thickness of the layer,
squeezing and straining increases the tracer flux across the layer on average,
all else equal.

Squeeze dispersion can matter in systems where mixing is inherently diffusive,
including, for example, the mixing of heat and carbon in the ocean's abyss.
More information about squeeze dispersion is given in our [paper that
was published in Geophysical Research Letters in 2019](https://glwagner.github.io/assets/pdf/squeeze-dispersion-GRL-2019.pdf).

### [FourierFlows.jl] 

[FourierFlows.jl] is [julia] software that solves fluid dynamics problems 
on CPUs and GPUs. I develop FourierFlows.jl with [Navid Constantinou].

[Subsurface internal waves]: http://www.livescience.com/42459-huge-ocean-internal-waves-explained.html
[quasi-geostrophic eddies]: https://en.wikipedia.org/wiki/Geostrophic_current
[FourierFlows.jl]: https://github.com/FourierFlows/FourierFlows.jl
[Navid Constantinou]: http://www.navidconstantinou.com
[CliMa]: https://clima.caltech.edu
[julia]: https://julialang.org
[Oceananigans.jl]: https://github.com/climate-machine/Oceananigans.jl
[dedalus]: http://dedalus-project.org
[Keaton Burns]: http://keaton-burns.com
[github]: https://github.com/glwagner
