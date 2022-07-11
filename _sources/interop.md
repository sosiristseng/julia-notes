# Interoperativity

Julia in conjuction with other programming languages.

- [Julia Interop](https://github.com/JuliaInterop) Organization

## Mathematica

- [MathLink.jl][] : Julia language interface for Mathematica/Wolfram Engine.

[MathLink.jl]: https://github.com/JuliaInterop/MathLink.jl

## Git

- [Git.jl](https://github.com/JuliaVersionControl/Git.jl) : Julia wrapper for command line Git.
- [GitHub.jl](https://github.com/JuliaWeb/GitHub.jl) : A Julia package for interfacing with the GitHub API.

## C

- Built-in [C interface](https://docs.julialang.org/en/v1/manual/calling-c-and-fortran-code/)
- [Clang.jl](https://github.com/JuliaInterop/Clang.jl) : A Julia language wrapper for libclang: the stable, C-exported interface to the LLVM Clang compiler.
- [CBinding.jl](https://github.com/analytech-solutions/CBinding.jl) : Automatically creating C library bindings with Julia at runtime.

## Cpp

- [CxxWrap.jl](https://github.com/barche/CxxWrap.jl) : A package to provide a Boost.Python-like wrapping for C+- types and functions to Julia.

"Might not work in the current version of Julia"
- 🏚️ [Cxx.jl](https://github.com/JuliaInterop/Cxx.jl/) : The Julia C+- Foreign Function Interface (FFI) with `@cxx` macro. Only works (out of the box) currently with Julia 1.1.x to 1.3.x.

## Erlang

- [ErlPort.jl](https://github.com/billosys/ErlPort.jl) : A Julia-Erlang module for use in the [erlport](http://erlport.org) project.

## Fortran

Built-in [ Fortran interface](https://docs.julialang.org/en/v1/manual/calling-c-and-fortran-code/).

## Java

### Running Java from Julia

- [JavaCall.jl](https://github.com/JuliaInterop/JavaCall.jl) : call Java programs from Julia.
- [JDBC.jl](https://github.com/aviks/JDBC.jl) : Julia interface to Java database drivers.
- [TeaSeis.jl](https://github.com/ChevronETC/TeaSeis.jl) : JavaSeis IO implementation for the Julia language.

### Running Julia from Java

[Discourse thread: Embedding Julia in the Java Virtual Machine](https://discourse.julialang.org/t/embedding-julia-in-the-java-virtual-machine/51444).

- [julia4j](https://github.com/rssdev10/julia4j) : Julia4J uses SWIG to build a Java Native Interface (JNI) integration with Julia.
- [libjulia-clj](https://github.com/cnuernber/libjulia-clj) : Julia bindings for Clojure JVM.

## JavaScript

- [JSExpr.jl](https://github.com/JuliaGizmos/JSExpr.jl) : Translate Julia to JavaScript.
- [Mustache.jl](https://github.com/jverzani/Mustache.jl) : Port of mustache.js to julia.
- [TableView.jl](https://github.com/JuliaComputing/TableView.jl) : an ag-grid based table viewer built on [WebIO.jl](https://github.com/JuliaGizmos/WebIO.jl).

## MATLAB

**See also** [matlab-to-julia](https://lakras.github.io/matlab-to-julia/) online translator.

**Packages**

- [Fmincon.jl](https://github.com/byuflowlab/Fmincon.jl) : Wrapper for MATLAB's `fmincon` function.
- [MAT.jl](https://github.com/JuliaIO/MAT.jl) : A Julia module for reading MATLAB files.
- [MATDaemon.jl](https://github.com/jondeuce/MATDaemon.jl) : Call Julia from MATLAB.
- [MATLAB.jl](https://github.com/JuliaInterop/MATLAB.jl) : an interface for using MATLAB® from Julia using the MATLAB C api.
- [Mex.jl](https://github.com/byuflowlab/Mex.jl) : Embedding Julia in the MATLAB process.

## ObjectiveC

- [ObjectiveC.jl](https://github.com/JuliaInterop/ObjectiveC.jl) : A Julia library that allows you to call Objective-C methods using native syntax.

## Python

- [Conda.jl](https://github.com/Luthaf/Conda.jl) : Conda managing Julia binary dependencies. e.g. for `IJulia.jl` and `PyPlot.jl`.
- [CondaPkg.jl](https://github.com/cjdoris/CondaPkg.jl) : Julia Pkg-like interface for the `conda` package mamanger.
- [FStrings.jl](https://github.com/magonser/FStrings.jl) : Implementation of Python style [fsrings](https://www.python.org/dev/peps/pep-0498/) literal string interpolation based on `Printf.@sprintf`.
- [PyCall.jl](https://github.com/JuliaPy/PyCall.jl) : Call Python functions from Julia.
- [PyJulia](https://github.com/JuliaPy/pyjulia) : Python interface to Julia. (Call Julia functions from Python)
- [PythonCall.jl](https://github.com/cjdoris/PythonCall.jl) : Bringing Python and Julia code in harmony. And you can also [call Julia from Python](https://github.com/cjdoris/PythonCall.jl#example-2-calling-julia-from-python).

## R

> - [Julia in Rmarkdown](https://cran.r-project.org/web/packages/JuliaCall/vignettes/Julia_in_RMarkdown.html) using [JuliaCall](https://rpubs.com/Consistency/310507).

- [RCall.jl](https://github.com/JuliaStats/RCall.jl) : Embedded R within Julia - ports all the `R` API functions from C into Julia.
- [RData.jl](https://github.com/JuliaData/RData.jl) : CodeIssues 5Pull requests 0Projects 0WikiSecurityInsightsRead R data files from Julia.
- [ReadStat.jl](https://github.com/WizardMac/ReadStat.jl) : Read files from Stata, SAS, and SPSS.


## REDUCE

- [Reduce.jl][] : Symbolic parser generator for Julia language expressions using REDUCE algebra term rewriter.
- [ReduceAlgebra.jl][] : Meta-package for [Reduce.jl][] and External Packages (e.g. [ReduceLinAlg.jl][])
- [ReduceLinAlg.jl][] : A selection of functions that are useful in the world of linear algebra.

[ReduceAlgebra.jl]: https://github.com/JuliaReducePkg/ReduceAlgebra.jl
[Reduce.jl]: https://github.com/chakravala/Reduce.jl
[ReduceLinAlg.jl]: https://github.com/JuliaReducePkg/ReduceLinAlg.jl


## Ruby

[Ruby interoperability](https://github.com/arbox/ruby-interoperability)

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [guard-julia](https://github.com/svs14/guard-julia) : Guard plugin for Julia development. Julia guard automatically launches respective tests when Julia files are modified.
- 🏗️ [jl4rb](https://github.com/rcqls/jl4rb) : Julia for Ruby embeds the julia language in ruby, with very basic julia types being converted to ruby objects.
- 🏗️🏚️ [ruby-julia](https://github.com/mrkn/ruby-julia) : Julia on Ruby (frequently updated, but supports Julia 1.1 only)

</details>

## Rust

- [jlrs](https://github.com/Taaitaaiger/jlrs): Julia bindings for Rust.
