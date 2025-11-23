@def title = "JuliaMolSim: Molecular Simulations in Julia"

# JuliaMolSim

![JuliaMolSim logo](/assets/juliamolsim.png)

Your friendly organisation about molecular and materials simulations in Julia.
You can also check us out on [GitHub](https://github.com/JuliaMolSim)!

@@colbox-blue
Rachel and Michael gave a
[keynote at Juliacon 2024](https://juliacon.org/2024/keynotes/#materials_modeling_bonding_across_atoms_code_and_people)
[*Materials Modeling: Bonding across atoms, code, and people*](https://michael-herbst.com/talks/2024.07.10_juliamolsim.pdf).
Their talk also covered the latest developments around JuliaMolSim.
[[Slides]](https://michael-herbst.com/talks/2024.07.10_juliamolsim.pdf) [[Youtube recording]](https://www.youtube.com/watch?v=zDh6LmEGUDc)
@@

## AtomsBase and AtomsCalculators ecosystem
- [**AtomsBase**](https://github.com/mfherbst/AtomsBase.jl):
  Rooted in our [Juliacon 2021](/juliacon21) meeting we started developing
  `AbstractSystem` ---
  an abstract interface for representing atomistic structures in Julia.
  The interface is still evolving, but already available in most packages
  from the JuliaMolSim ecosystem to facilitate the exchange of atomistic structures.
- [**AtomsCalculators**](https://github.com/JuliaMolSim/AtomsCalculators.jl):
  A more recent effort, started in 2023, to provide a unified interface
  for computing key atomistic properties of structures, including
  energies, forces, virial stresses.

The following packages are part of the JuliaMolSim and based
on the above interfaces.
We also feature a few packages for
[cross-ecosystem links](#cross-ecosystem_links).

## Building and loading atomistic structures
- [AtomsBuilder.jl](https://github.com/JuliaMolSim/AtomsBuilder.jl):
  Package for building structures as `AbstractSystem` (surfaces, defects, ...)
- [AtomsIO.jl](https://github.com/mfherbst/AtomsIO.jl):
  Read and write structures/trajectories to a variety of file formats

## Some AtomsCalculators
- [ACEpotentials.jl](https://github.com/ACEsuit/ACEpotentials.jl): Interatomic potential learning using the Atomic cluster expansion; see also [ACEsuit](https://github.com/ACEsuit) for related packages.
- [DFTK.jl](https://dftk.org): A flexible code for density-functional theory simulations
- [EmpiricalPotentials.jl](https://github.com/JuliaMolSim/EmpiricalPotentials.jl)
  and [InteratomicPotentials.jl](https://github.com/cesmix-mit/InteratomicPotentials.jl):
  Simple parametrised materials potentials (EAM, LJ, ...)

## Dynamics and atomic arrangements
- [GeometryOptimization.jl](https://github.com/JuliaMolSim/GeometryOptimization.jl/):
  Optimise atomistic structures (atomic positions and lattices)
  based on a framework featuring generic optimisers.
- [Molly.jl](https://juliamolsim.github.io/Molly.jl/stable/):
  Molecular simulation in Julia

## Cross-ecosystem links
- [ASEconvert.jl](https://github.com/mfherbst/ASEconvert.jl):
  Integration with the [Atomistic Simulation Environment (ASE)](https://wiki.fysik.dtu.dk/ase/index.html): Use ASE Atoms as `AbstractSystem`,
  use ASE Calculators as `AbstractCalculator`.
- [IPICalculator.jl](https://github.com/JuliaMolSim/IPICalculator.jl/):
  Two-way integration with the [IPI socket protocol](https://ipi-code.org/);
  enables usage of Julia calculators in external ecosystems and vice versa
  usage of external calculators in Julia.

## Other packages
Some other packages for molecular and materials modelling worth mentioning:
- [Wannier.jl](https://github.com/qiaojunfeng/Wannier.jl):
  Wannier localisation of electronic structures
- [FreeBird.jl](https://github.com/wexlergroup/FreeBird.jl):
  Free energy calculators by Bayesian-inspired nested sampling and other integration techniques.

## Contacting us
[zulip-url]: https://juliamolsim.zulipchat.com/register/
[slack-url]: https://julialang.org/slack/

We have a community call on the **third Monday of each month at 12:15pm US Eastern time**. Details can be found on the [Julia Events Calendar](https://julialang.org/community/#events).

Get involved in ongoing (and slightly less synchronous) conversations by joining our [Zulip chat][zulip-url]!

There is also a #juliamolsim channel on the [Julia Slack][slack-url],
but we make fewer promises about checking this regularly...

## Virtual meetings
- [Birds of Feather at JuliaCon 2021](/juliacon21)
- [Minisymposium at JuliaCon 2022](/juliacon22)
