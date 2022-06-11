# Graph Theory

General graph data structures, algorithms in Julia.

- [Wikipedia : Graph Theory](https://en.wikipedia.org/wiki/Graph_theory)
- [Julia Graphs](https://github.com/JuliaGraphs) organization.

## File I/O for Graphs

- [GraphIO.jl](https://github.com/JuliaGraphs/GraphIO.jl) : GraphIO provides support to [Graphs.jl][] for reading/writing graphs in various formats.
- [SNAPDatasets.jl](https://github.com/JuliaGraphs/SNAPDatasets.jl) : [Graphs.jl][]-formatted graph files taken from the [SNAP Datasets](https://snap.stanford.edu/data/index.html) collection.

## Graph data types

- [AbstractTrees.jl](https://github.com/JuliaCollections/AbstractTrees.jl) : Abstract julia interfaces for working with trees.
- [Arrowhead.jl](https://github.com/ivanslapnicar/Arrowhead.jl) : Arrowhead and Diagonal-plus-rank-one Eigenvalue Solvers.
- [Graphs.jl][] : An optimized graphs package for the Julia programming language. The successor of [LightGraphs.jl][].
- [GraphsExtras.jl](https://github.com/JuliaGraphs/GraphsExtras.jl) : Additional functionality for [Graphs.jl][].
- [MetaGraphs.jl](https://github.com/JuliaGraphs/MetaGraphs.jl) : [Graphs.jl][] data structures with multiple heterogeneous metadata.
- [Multigraphs.jl](https://github.com/QuantumBFS/Multigraphs.jl) : A multigraph extension of [Graphs.jl][].
- [SimpleGraphs.jl](https://github.com/scheinerman/SimpleGraphs.jl) : A module for working with simple graphs (no loops, no multiple edges, no directed edges).
- [SimpleHypergraphs.jl](https://github.com/pszufe/SimpleHypergraphs.jl) : A simple hypergraphs package for the Julia programming language.
- [SimpleValueGraphs.jl](https://github.com/simonschoelly/SimpleValueGraphs.jl) : A [Graphs.jl][] compatible package for graphs with multiple, homogeneous vertex, edge and graph metadata.
- [SimpleWeightedGraphs.jl](https://github.com/JuliaGraphs/SimpleWeightedGraphs.jl) : Edge-Weighted Graphs for [Graphs.jl][].

[Graphs.jl]: https://github.com/JuliaGraphs/Graphs.jl
[LightGraphs.jl]: https://github.com/sbromberger/LightGraphs.jl

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Seep.jl](https://github.com/mit-ll/Seep.jl) : It builds and evaluates computational flow graphs in julia.

</details>

## Graph algorithms

- [CommunityDetection.jl](https://github.com/JuliaGraphs/CommunityDetection.jl) : Implements community detection for [Graphs.jl][].
- [Dendriform.jl](https://github.com/chakravala/Dendriform.jl) : Dendriform di-algebra algorithms to compute using Loday's arithmetic on groves of planar binary trees.
- [GraphDataFrameBridge.jl](https://github.com/JuliaGraphs/GraphDataFrameBridge.jl) : Tools for interoperability between DataFrame objects and LightGraphs and MetaGraphs objects.
- [GraphsFlows.jl](https://github.com/JuliaGraphs/GraphsFlows.jl) : [Flow algorithms](https://en.wikipedia.org/wiki/Maximum_flow_problem) on top of [Graphs.jl][]
- [GraphsMatching.jl](https://github.com/JuliaGraphs/GraphsMatching.jl) : Matching algorithms for [Graphs.jl][].
- [LayeredLayouts.jl](https://github.com/oxinabox/LayeredLayouts.jl) : Layered Layout Algorithms for Directed Acyclic Graphs (DAGs).
- [MatrixNetworks.jl](https://github.com/nassarhuda/MatrixNetworks.jl) : Graph and Network algorithms.
- [NetworkLayout.jl](https://github.com/JuliaGraphs/NetworkLayout.jl) : Layout algorithms for graphs and trees in pure Julia.
- [RobustShortestPath.jl](https://github.com/chkwon/RobustShortestPath.jl) : Robust Shortest Path Finder.
- [SuiteSparseGraphBLAS.jl](https://github.com/JuliaSparse/SuiteSparseGraphBLAS.jl) : Julia wrapper for SuiteSparse:GraphBLAS.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [RepresentationTheory.jl](https://github.com/dlfivefifty/RepresentationTheory.jl) : representation theory of the symmetric group. (No `Project.toml`)

</details>

**Resources**

- [aleph_star](https://github.com/imagry/aleph_star) : Reinforcement learning with A* and a deep heuristic.
- [Wikipedia: Graphal gorithms](https://en.wikipedia.org/wiki/Category:Graph_algorithms)

## Visualizing Graphs

See also the [Visualizations](./visualization.md) section.

- [GraphPlot.jl](https://github.com/afternone/GraphPlot.jl) : Graph visualization for Julia.
- [GraphRecipes.jl](https://github.com/JuliaPlots/GraphRecipes.jl) : Graph-related recipes to be used with Plots.jl.
- [VegaGraphs.jl](https://github.com/JuliaGraphs/VegaGraphs.jl) : Graph visualization with [Vega-Lite](https://github.com/queryverse/VegaLite.jl).
