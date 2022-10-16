---
title: A few things I work on
header:
  image: /assets/images/blueoffice-2.jpg
permalink: /projects/
---

Have questions about my work? Email me at
`gregory.leclaire.wagner@gmail.com`. 
See my [github] for real-time updates on my software projects.

### Turbulent ocean mixing

I develop models for vertical turbulent mixing in the ocean surface boundary layer
(at scales between 1 and 100 meters), and for horizontal mixing by ocean mesoscale eddies
(at scales from 10-200 kilometers). The models I work on are physics-based,
but leverage powerful data-driven techniques for parameter estimation
and uncertainty quantification. This work is part of the [CliMa] project.

### [Oceananigans.jl]

I'm one of the core developers of CliMa's ocean component, [Oceananigans.jl]. 
[Oceananigans.jl] is a fast and friendly software for ocean problems
that range from idealized class room problem, to high-resolution, ~1 meter
large eddy simulations, to planetary-scale general circulation simulations.

![Oceananigans docs](/assets/figures/oceananigans_docs.png)

[Oceananigans.jl] is written in the Julia programming 
language and runs on CPUs and GPUs. I've helped develop Oceananigans'
ground-breaking user interface and the sustainable, extensible design of
its internal.

### Surface gravity waves and wave-turbulence interactions

Frothing, whitecapping, undulating surface waves are the top of the
ocean surface boundary layer. I work both on the theory of surface
wave forcing and momentum transfer between the atmosphere and ocean, and
on interactions between surface waves and boundary layer turbulence.

The image below depicts turbulence simulated by
[Oceananigans.jl]. The image shows the turbulent vertical velocity field
that develops following the growth of a surface wave field with 
a wave length of one hundred meters over four hours.

![Forced growth](/assets/figures/forced_growth.png)

Information about how to produce this image can be found
[on github](https://github.com/glwagner/WaveTransmittedTurbulence.jl),
or in [this paper](https://glwagner.github.io/assets/pdf/near-inertial-waves-turbulence-growth-swell-preprint.pdf).

I've also co-written a [paper](https://glwagner.github.io/assets/pdf/Stokes-drift-ocean-circulation-Wagner-Constantinou-Reichl.pdf)
on a common source of confusion in studies on ocean transport:
how to interpret general circulation model output when that model does _not_ depend
explicitly on the ocean surface gravity wave field.

[Subsurface internal waves]: http://www.livescience.com/42459-huge-ocean-internal-waves-explained.html
[quasi-geostrophic eddies]: https://en.wikipedia.org/wiki/Geostrophic_current
[FourierFlows.jl]: https://github.com/FourierFlows/FourierFlows.jl
[Navid Constantinou]: http://www.navidconstantinou.com
[CliMa]: https://clima.caltech.edu
[julia]: https://julialang.org
[Oceananigans.jl]: https://clima.github.io/OceananigansDocumentation/stable/
[dedalus]: http://dedalus-project.org
[Keaton Burns]: http://keaton-burns.com
[github]: https://github.com/glwagner
