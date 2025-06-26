# Joao Hespanha's registry of Julia packages 

## Installation

To add this registry to Julia:

```julia
using Pkg
pkg"registry add General https://github.com/HespanhaPublic/HespanhaRegistry.jl"
```

Some of the repositories in this registry are private and will not work for most people.

## Updating package

The recommended way to register a package or a new version of a package is to 

1) Activate the package to register, e.g., by starting in the package home directory with

   ```bash
   julia --project=.
   ```

2) Execute

   ```julia
   using LocalRegistry
   register()
   ```

> [!warning]
> For this to work the package version must be higher than the one previously registered.
