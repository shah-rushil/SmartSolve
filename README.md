# SmartSolve. Proof of concept.

SmartSolve aims to significantly accelerate various linear algebra algorithms based on providing better algorithmic and architectural choices. In the following example SmartSolve is used to automatically generate SmartLU, an optimized version of the LU decomposition.

```bash
cd SmartSolve/examples
julia --project=.
```

```julia
pkg> instantiate
julia> include("generate_smartlu.jl")
```
