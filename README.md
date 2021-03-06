# QSimulator

[![Build Status](https://travis-ci.org/BBN-Q/QSimulator.jl.svg)](https://travis-ci.org/BBN-Q/QSimulator.jl)

Unitary and Lindbladian evolution of quantum states in Julia.

In order to use it, run 

```julia
Pkg.clone("git@github.com:BBN-Q/QSimulator.jl.git")
```

## Dependencies

QSimulator uses Julia 0.4 compatible syntax.  It also depends on two Julia packages not yet registered with METADATA.jl:
* [QuantumInfo.jl](https://bitbucket.org/marcusps/quantuminfo.jl)
* [ExpmV.jl](https://github.com/marcusps/ExpmV.jl)
