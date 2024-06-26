```@meta
CurrentModule = PhyloCoalSimulations
```

# PhyloCoalSimulations

[PhyloCoalSimulations](https://github.com/juliaphylo/PhyloCoalSimulations.jl)
is a [Julia](http://julialang.org) package to
simulate phylogenies under the coalescent.
It depends on [PhyloNetworks](https://github.com/juliaphylo/PhyloNetworks.jl)
for the phylogenetic data structures, and manipulation of phylogenies.

References:
please see [bibtex entries here](https://github.com/juliaphylo/PhyloCoalSimulations.jl/blob/main/CITATION.bib).

- for this package and the network coalescent model with inheritance correlation:\
  Fogg, Allman & Ané (2023).
  PhyloCoalSimulations: A simulator for network multispecies coalescent models,
  including a new extension for the inheritance of gene flow.
  [Systematic Biology](https://academic.oup.com/sysbio/advance-article/doi/10.1093/sysbio/syad030/7187011?guestAccessKey=616778e9-ea09-4e4e-9853-229499b5f068),
  72(5):1171–1179.
  [doi:10.1093/sysbio/syad030](https://doi.org/10.1093/sysbio/syad030).

- for [PhyloNetworks](https://github.com/juliaphylo/PhyloNetworks.jl),
  which this package depends on:\
  Solís-Lemus, Bastide & Ané (2017).
  PhyloNetworks: a package for phylogenetic networks.
  [Molecular Biology and Evolution](https://academic.oup.com/mbe/article/doi/10.1093/molbev/msx235/4103410/PhyloNetworks-a-package-for-phylogenetic-networks?guestAccessKey=230afceb-df28-4160-832d-aa7c73f86369),
  34(12):3292–3298.
  [doi:10.1093/molbev/msx235](https://doi.org/10.1093/molbev/msx235)

For a tutorial, see the manual:

```@contents
Pages = [
    "man/getting_started.md",
    "man/mapping_genetree_to_network.md",
    "man/converting_coal2generation_units.md",
    "man/correlated_inheritance.md",
    "man/more_examples.md",
]
Depth = 3
```

For help on individual functions, see the library:

```@contents
Pages = [
    "lib/public.md",
    "lib/internal.md",
]
Depth = 3
```
