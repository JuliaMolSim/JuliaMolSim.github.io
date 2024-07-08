@def title = "JuliaMolSim: Molecular Simulations in Julia"

# JuliaMolSim

![JuliaMolSim logo](/assets/juliamolsim.png)

Your friendly organisation about molecular and materials simulations in Julia.
You can also check us out on [GitHub](https://github.com/JuliaMolSim)!

@@colbox-blue
Rachel and Michael will give a
[keynote at Juliacon 2024](https://juliacon.org/2024/keynotes/#materials_modeling_bonding_across_atoms_code_and_people)
*Materials Modeling: Bonding across atoms, code, and people*.
Their talk will also cover the latest developments around JuliaMolsim.
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

Integrating with the above interfaces are the following packages
from the JuliaMolSim ecosystem:

- [AtomsBuilder.jl](https://github.com/JuliaMolSim/AtomsBuilder.jl):
  Package for building structures as `AbstractSystem`s (surfaces, defects, ...)
- [AtomsIO.jl](https://github.com/mfherbst/AtomsIO.jl):
  Read and write structures/trajectories to a variety of file formats
- [ACEpotentials.jl](https://github.com/ACEsuit/ACEpotentials.jl): Interatomic potential learning using the Atomic cluster expansion; see also [ACEsuit](https://github.com/ACEsuit) for related packages.
- [DFTK.jl](https://dftk.org): A flexible code for density-functional theory simulations
- [EmpiricalPotentials.jl](https://github.com/JuliaMolSim/EmpiricalPotentials.jl)
  and [InteratomicPotentials.jl](https://github.com/cesmix-mit/InteratomicPotentials.jl):
  Simple parametrised materials potentials (EAM, LJ, ...)
- [Molly.jl](https://juliamolsim.github.io/Molly.jl/stable/):
  Molecular simulation in Julia

## Other packages
Some other packages for molecular and materials modelling worth mentioning:
- [Wannier.jl](https://github.com/qiaojunfeng/Wannier.jl):
  Wannier localisation of electronic structures

## Contacting us
[zulip-url]: https://juliamolsim.zulipchat.com/register/
[slack-url]: https://julialang.org/slack/
Get involved in ongoing conversations by joining our [Zulip chat][zulip-url]!

There is also a #juliamolsim channel on the [Julia Slack][slack-url],
but we make fewer promises about checking this regularly...

## Virtual meetings
- [Birds of Feather at JuliaCon 2021](/juliacon21)
- [Minisymposium at JuliaCon 2022](/juliacon22)
