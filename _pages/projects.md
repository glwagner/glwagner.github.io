---
title: The things that keep me up at night
header:
  image: /assets/images/blueoffice-2.jpg
permalink: /projects/
---

### Squeeze dispersion

Squeeze dispersion is a phenomenon by which the dispersion of tracers
is enhanced in the presence of fluctuating strain. 
This process is important in systems where mixing is inherently diffusive 
--- for example, oceanic mixing across density surfaces. 
This work shows that averages of diffusivity tend to 
underestimate the 'true' diffusivity that is obtained by 'correctly'
averaging and normalizing tracer flux estimates in the presence of strain.

### Internal waves and currents

[Subsurface internal waves] modify the physics of [quasi-geostrophic eddies]
and turbulence on scales from 10 to 100 km ---
the ocean's version of storms and cyclones --- that play 
a crucial role in transporting heat and carbon from equator to pole and 
determining the ocean's density structure. The precise nature and importance
of these interactions in the Earth's ocean, and the role that waves
play in transporting oceanic tracers, is poorly understood.

### Surface boundary layer mixing

I've just started work to develop a parameterization for mixing 
in the ocean's surface boundary layer for [Clima].

### [dedaLES]

[dedaLES] is python software that uses the [dedalus] framework 
to provide solvers for Large Eddy Simulation of turbulence systems
on both laptops and supercomputers. [dedaLES] is modular, so that
fluid models (compressible turbulence, stratified turbulence, etc) 
and turbulence closures can be easily mixed and matched. 
My goal is to use [dedaLES] to model turbulence mixing in the oceanic 
surface boundary layer. I am developing [dedaLES] with [Keaton Burns].

### [FourierFlows.jl] 

[FourierFlows.jl] is [julia] software that solves 'small' 2D fluid 
dynamics problems on CPUs and GPUs. I am developing FourierFlows.jl
with [Navid Constantinou].

[Subsurface internal waves]: http://www.livescience.com/42459-huge-ocean-internal-waves-explained.html
[quasi-geostrophic eddies]: https://en.wikipedia.org/wiki/Geostrophic_current
[FourierFlows.jl]: https://github.com/FourierFlows/FourierFlows.jl
[Navid Constantinou]: http://www.navidconstantinou.com
[manuscript on Squeeze Dispersion]: https://glwagner.github.io/assets/pdf/squeezedispersiondraft.pdf
[Clima]: https://clima.caltech.edu
[julia]: https://julialang.org
[dedaLES]: https://github.com/glwagner/dedaLES
[dedalus]: http://dedalus-project.org
[Keaton Burns]: http://keaton-burns.com
