# Papers:

If the paper has a description, Blake has read it and written what might be useful. If it is checked off, someone else has hopefully read it too or Blake made a decision about it.
Depending on how long this list becomes, it might make more sense to put it in an obsidian graph organized by citation and topic.
- [ ] [Real-time Ray Traced Ambient Occlusion and Animation: Image quality and performance of hardware- accelerated ray traced ambient occlusion](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1574351&dswid=5090)
	- Performance comparison between GTAO, SSAO, and RTAO
	- Higher performance requirement for RTAO but for modern cards this is less of an issue.
- [ ] [Real Time Graphics Rendering Capabilities of Modern Game Engines](https://pergamos.lib.uoa.gr/uoa/dl/object/2812851/file.pdf)
	- Analysis of Unreal 4, Unity, and GameMaker Studio
	- Implementation of Screen Space Directional Occlusion
	- Goes over many methods in detail
- [ ] [Real-time photorealistic rendering for mobile devices](https://ieeexplore.ieee.org/abstract/document/6776103?casa_token=dQY9GterVfUAAAAA:XAzYKcVYnJRbS8S1S-rNt6OzVa710N6u45kmEGlLN1VslYsfj3T15DQ_TPDhGEzFhDWUDZVRdA)
	- spherical harmonics + ambient occlusion for environment lights
	- optimized for low power devices
- [ ] [Approximating dynamic global illumination in image space](https://dl.acm.org/doi/abs/10.1145/1507149.1507161?casa_token=E55aKeyNveQAAAAA:_R5pO0jk6xP1MHd32DgXoWyo2Y0xpPVnSCOgs_lnGkgE43_NZq-UEAZcqJF4qNRPVqAlG-LCHzv6KQ)
	- cant access - also from 2009
- [ ] [Image-Space Horizon-Based Ambient Occlusion](https://dl.acm.org/doi/pdf/10.1145/1401032.1401061?casa_token=ntWZuT3y_S4AAAAA:wLP1Jh_53QzX1WzeLg8t5Y5GSJIAOYd_mKPZcglM0U1wANpnj4tdv0ilFMxX6FheGrvIMVGtje82aA)
- [ ] [The rendering equation](https://dl.acm.org/doi/abs/10.1145/15922.15902)
- [ ] [A two-pass solution to the rendering equation: A synthesis of ray tracing and radiosity methods](https://dl.acm.org/doi/abs/10.1145/37402.37438)
- [ ] [Animating sand as a fluid](https://dl.acm.org/doi/abs/10.1145/1073204.1073298?casa_token=DmefUdroV08AAAAA:zTRCLa35oOAEBKzwcNepvS7nYwVYiyKszpQnOBPaxLppTpT_rp5ZAaeqnQxINpMvXkFHaEvP_lRoEg)
	- Turned a fluid sim into a sand simulation
- [ ] [Animating Sand, Mud, and Snow](https://doi.org/10.1111/1467-8659.00299)
	- representing sand as a grid that could easily be a displacement map. Particles do not appear to be preserved, but this paper has the same end result as the stamps Finley is making. Its primary constraint was that it was done in 1999 and the hardware was not there
- [ ] [Real-time Animation of Sand-Water Interaction](https://doi.org/10.1111/j.1467-8659.2008.01336.x)
	- particle simulation for the sand
- [ ] [sand surface flow](https://cs.dartmouth.edu/~bozhu/papers/sand_surface_flow.pdf)
	- particle simulation - combination of static geometry with particle simulation above it
- [ ] [DyRT: dynamic response textures for real time deformation simulation with graphics hardware](https://dl.acm.org/doi/abs/10.1145/566570.566621)
	- Precalculated deformation for animated bones
- [ ]  [A material point method for snow simulation](https://doi.org/10.1145/2461912.2461948)
	- particle simulation
- [ ] [Drucker-prager elastoplasticity for sand animation](https://doi.org/10.1145/2897824.2925906)
	- Uses material point method (MPM) and adds stress-projection
- [ ] [SPH granular flow with friction and cohesion](https://doi.org/10.1145/2019406.2019410)
	- Smoothed particle hydrodynamics. 
- [ ] [XPBI: Position-Based Dynamics with Smoothing Kernels Handles Continuum Inelasticity](https://doi.org/10.1145/3680528.3687577)
	- Update of SPH - it might just be better to look at the paper. This came out in 2024 and looks awesome. Fig17 (total computational cost) is interesting. This simulation is not real time and is not optimized for GPU.
- [ ] [Particle-based simulation of granular materials](https://doi.org/10.1145/1073368.1073379)
	- particle simulation (2005)
- [ ] [Hybrid grains: adaptive coupling of discrete and continuum simulations of granular media](https://doi.org/10.1145/3272127.3275095)
	- Another particle simulation
- [ ] [An implicit compressible SPH solver for snow simulation](https://doi.org/10.1145/3386569.3392431)
	- Based on SPH, specifically for snow. Includes sticking and compression.
- [ ] [Free-flowing granular materials with two-way solid coupling](https://doi.org/10.1145/1866158.1866195)
	- Early paper on particle simulations (2010)
- [ ] [Literature review: Snow and Ice Animation Methods in Computer Graphics](https://doi.org/10.1111/cgf.15059)
	- 2024 literature review on snow and ice. Contains useful comparisons of existing methods and how they relate to each other.
- [ ] [Real-time Height-field Simulation of Sand and Water Mixtures](https://doi.org/10.1145/3610548.3618159)
	- Primarily a fluid simulation (water flowing over terrain)

# Areas that still need to be explored:
- [ ] Other types of simulations
- [ ] cloth/character simulations - especially ones that happen in real time
	- [ ] weight painting?
- [ ] Simulation methods other than SPH and MPM
- [ ] GPU simulations
