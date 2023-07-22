# NestedSampling
Constant volume nested sampling algorithm for the Lennard-Jones potential implemented in Julia.

## nestedsampling.jl
This file uses the potential.jl, randwalk.jl, and sample.jl files to implement the NS algorithm.

## potential.jl
The file potential.jl encloses a function that returns the total energy of a given configuration. The current file uses the LJ-potential to compute the energy, but any potential model may be implemented within this file.

## randwalk.jl
This file takes a given configuration and does a random walk on it, keeping the energy lower than or equal to the initial configuration.

## sample.jl
This file creates a new random configuration.
