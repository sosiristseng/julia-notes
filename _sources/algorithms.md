# Algorithms

> General algorithms for Julia.

**Packages**

- [CRC.jl](https://github.com/andrewcooke/CRC.jl) : a Julia module for calculating Cyclic Redundancy Checksums (CRCs).
- [ECC.jl](https://gitlab.com/braneproject/ECC.jl) : Elliptic Curve Cryptography in Julia (secp256k1 curve)

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Codecs.jl](https://github.com/BioJulia/Codecs.jl) : Common data encoding algorithms: Base64, Zlib, and Binary Coded Decimal. (No `Project.toml`)

</details>

## Sorting

- [NaturalSort.jl](https://github.com/JuliaStrings/NaturalSort.jl) : [Natural sort order](https://en.wikipedia.org/wiki/Natural_sort_order).
- [SortingAlgorithms.jl](https://github.com/JuliaCollections/SortingAlgorithms.jl) : extra sorting algorithms extending Julia's sorting API.
- [SortingLab.jl](https://github.com/xiaodaigh/SortingLab.jl) : Experimental implementations of sorting algorithms.

## Pattern Matching

- [BlossomV.jl](https://github.com/mlewe/BlossomV.jl) : An interface for the Blossom V perfect matching algorithm.
- [Loess.jl](https://github.com/JuliaStats/Loess.jl) : is a loess implementation based on the fast kd-tree based approximation algorithm, a space-partitioning data structure for organizing points in a k-dimensional space.
- [Match.jl](https://github.com/kmsquire/Match.jl) : Advanced Pattern Matching for Julia.
- [MLStyle.jl](https://github.com/thautwarm/MLStyle.jl) : providing multiple productivity tools from ML (Meta Language) like pattern matching `@match`.


<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [JellyFish.jl](https://github.com/samuelcolvin/JellyFish.jl) : Port of the jellyfish string comparison library. (No `Project.toml`)

</details>


## NP-complete Problems

[Wikipedia: NP-complete](https://en.wikipedia.org/wiki/Category:NP-complete_problems) problems cannot be solved in polynomial time complexity and often have to be inexactly solved using heuristics.

- [TravelingSalesmanHeuristics.jl](https://github.com/evanfields/TravelingSalesmanHeuristics.jl) : Julia package for simple traveling salesman problem heuristics.

### Boolean satisfiability problem (SAT)

[Wikipedia: SAT](https://en.wikipedia.org/wiki/Satisfiability_modulo_theories) is a kind of NP-complete (NPC) problems.

- [PicoSAT.jl](https://github.com/jakebolewski/PicoSAT.jl) : Provides Julia bindings to the popular SAT solver [picosat](http://fmv.jku.at/picosat/) by Armin Biere. It is based off the Python pycosat and Go pigosat bindings written by Ilan Schnell and Willam Schwartz.
- [SimpleSATSolver.jl](https://github.com/dpsanders/SimpleSATSolver.jl) : A (very) simple SAT solver in pure Julia.

## Genetic algorithm

[Wikipedia: Genetic algorithm](https://en.wikipedia.org/wiki/Genetic_algorithm)

- [Evolutionary.jl](https://github.com/wildart/Evolutionary.jl) : Evolutionary & genetic algorithms for Julia.

## Resources

- [Awesome algorithms](https://github.com/tayllan/awesome-algorithms), a curated list of awesome places to learn and/or practice algorithms.
- [BeautifulAlgorithms.jl](https://github.com/mossr/BeautifulAlgorithms.jl) : Concise and beautiful algorithms written in Julia.
- [study @ codematician](https://github.com/codematician/study) : A study of interesting algorithms in Python.
- [Project_Euler_Julia.ipynb](https://nbviewer.org/github/punkrockpolly/Playing-with-Julia/blob/master/Project_Euler_Julia.ipynb) : Solutions to [Project Euler](https://projecteuler.net) Problems, algorithm & math puzzles.
