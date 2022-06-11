# Julia Programming Paradigms

- [Wikipedia: Programming Paradigms](https://en.wikipedia.org/wiki/Programming_paradigm)
- [Basic Language Comparison](https://github.com/JulesKouatchou/basic_language_comparison) : Basic Comparison of Various Computing Languages, eg. Python, Julia, Matlab, IDL, R, Java, Scala, C, Fortran.
- [Programming Language Theory](https://github.com/steshaw/plt)

## Automata

- [Wikipedia: Automata](https://en.wikipedia.org/wiki/Category:Automata_(computation))
- [Wikipedia: Finite Automata](https://en.wikipedia.org/wiki/Category:Finite_automata)

**Packages**

- [Automa.jl](https://github.com/BioJulia/Automa.jl) : A julia code generator for regular expressions - this package can do text validation, parsing, and tokenizing based on state machine compiler.
- [CodeTracking.jl](https://github.com/timholy/CodeTracking.jl) : An extension of Julia's InteractiveUtils library that provides an interface for obtaining strings and expressions of method definitions, method signatures, etc.. designed to work with Revise.jl (for versions v1.1.0 and higher).
- [MacroTools.jl](https://github.com/FluxML/MacroTools.jl) : A library providing helpful tools for writing macros, notably a very simple templating system with some functions

## Control Flow

- [Wikipedia: Control Flow](https://en.wikipedia.org/wiki/Category:Control_flow)
- [Julia docs: Control flow](https://docs.julialang.org/en/v1/manual/control-flow/)

**Packages**

- [CommonSubexpressions.jl](https://github.com/rdeits/CommonSubexpressions.jl) : Naïve combined subexpression elimination in Julia.
- [ControlSystems.jl](https://github.com/JuliaControl/ControlSystems.jl) : A Control Systems Toolbox for Julia.
- [IterTools.jl](https://github.com/JuliaCollections/IterTools.jl) : Common functional iterator patterns.
- [LinearControl.jl](https://github.com/jemofthewest/LinearControl.jl) : Julia package for analysis and design of control strategies for linear systems.
- [ProtoBuf.jl](https://github.com/JuliaIO/ProtoBuf.jl) : A Julia implementation for protocol buffers, a language-neutral, platform-neutral, extensible way of serializing structured data for use in communications protocols, data storage, and more.

### Reversible programming

- [Wikipedia: reversible programming](https://en.wikipedia.org/wiki/Reversible_computing)

**Packages**

- [NiLang.jl](https://github.com/GiggleLiu/NiLang.jl) : a reversible domain-specific language (DSL). Every state change can be undone.

## Functional Programming

- [Wikipedia: Declarative Programming](https://en.wikipedia.org/wiki/Declarative_programming)
- [Wikipedia: Functional Programming](https://en.wikipedia.org/wiki/Functional_programming)

**Packages**

- [Chain.jl](https://github.com/jkrumbiegel/Chain.jl) : A Julia package for piping a value through a series of transformation expressions using a convenient syntax.
- [Glob.jl](https://github.com/vtjnash/Glob.jl) : Posix-compliant file name pattern matching.
- [Lazy.jl](https://github.com/MikeInnes/Lazy.jl) : Functional programming for Julia with lazily-evaluated lists and a large library of functions for working with them.
- [LispREPL.jl](https://github.com/swadey/LispREPL.jl) : REPL for `Lisp.jl`.
- [LispSyntax.jl](https://github.com/swadey/LispSyntax.jl) : lisp-like language in julia.
- [Monads.jl](https://github.com/pao/Monads.jl) : Monadic expressions and sequences for Julia. [hSee the doc](https://monadsjl.readthedocs.org/).
- [Pipe.jl](https://github.com/oxinabox/Pipe.jl) : Improved function piping in Julia.

## Reactive Programming

[Wikipedia: Reactive Programming](https://en.wikipedia.org/wiki/Reactive_programming)

- [Pluto.jl](https://github.com/fonsp/Pluto.jl) : Simple reactive notebooks for Julia.
- [Reactive.jl](https://github.com/JuliaGizmos/Reactive.jl) : A package for reactive programming in Julia.
- [Rocket.jl](https://github.com/biaslab/Rocket.jl) : A functional reactive programming extensions library for Julia.

## Design by contract

[Wikipedia: Design by contract](https://en.wikipedia.org/wiki/Design_by_contract)

- [DesignByContract.jl](https://github.com/ghaetinger/DesignByContract.jl) : an interface for Design By Contract programming in Julia. See also [Eiffel](https://www.eiffel.org/doc/eiffel/Learning_Eiffel), which first introduced Design By Contract programming.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- [Contracts.jl](https://github.com/eschnett/Contracts.jl) : macros for pre- and post-conditions in functions. (No `Project.toml`)

</details>

## Interpreters

[Wikipedia: Interpreters](https://en.wikipedia.org/wiki/Category:Interpreters_(computing))

- [JuliaInterpreter.jl](https://github.com/JuliaDebug/JuliaInterpreter.jl) : Interpreter for Julia code.

## Transplier

[Wikipedia: Transpilers](https://en.wikipedia.org/wiki/Source-to-source_compiler)

- [Transpilers.jl](https://github.com/kskyten/Transpilers.jl) : a common interface for transpiling code into Julia.

## Macro and Metaprogramming

**Resources**

- [Wikipedia: Macro](https://en.wikipedia.org/wiki/Macro_(computer_science))
- [Wikipedia: Metaprogramming](https://en.wikipedia.org/wiki/Metaprogramming)
- [Julia docs: Metaprogramming](https://docs.julialang.org/en/v1/manual/metaprogramming/#Metaprogramming)

**Packages**

- [SyntaxTree.jl](https://github.com/chakravala/SyntaxTree.jl) : Toolset for modifying Julia AST and characteristic vlues.
- [Unroll.jl](https://github.com/StephenVavasis/Unroll.jl) : A julia macro for unrolling conditional `for` loops.\

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [ForceImport.jl](https://github.com/chakravala/ForceImport.jl) : Macro that force imports conflicting methods in Julia modules. (No `Project.toml`)

</details>

## Automatic Programming

**Resources**

[Wikipedia: Automatic Programming](https://en.wikipedia.org/wiki/Automatic_programming)

**Packages**

- [Cassette.jl](https://github.com/JuliaLabs/Cassette.jl) : a Julia package that provides a mechanism for dynamically injecting code transformation passes into Julia’s just-in-time (JIT) compilation cycle, enabling post hoc analysis, optimization, and modification of "Cassette-unaware" Julia programs.
- [IRTools.jl](https://github.com/FluxML/IRTools.jl) : Intermediate Representation toolkit to provide a simple and flexible IR format, expressive enough to work with both lowered and typed Julia code, as well as external IRs. It can be used with Julia metaprogramming tools such as Cassette.
- [Revise.jl](https://github.com/timholy/Revise.jl) : Automatically update function definitions in a running Julia session. It will help you keep your sessions running longer, reducing the need to restart Julia whenever you make changes to code.


## Program Analysis

**Resources**

- [Wikipedia: Program Analysis](https://en.wikipedia.org/wiki/Category:Program_analysis)\
- [Julia docs: profiling](https://docs.julialang.org/en/v1/manual/profile/).

**Packages**

- [CallGraphs.jl](https://github.com/timholy/CallGraphs.jl) : A package for analyzing source-code callgraphs, particularly of Julia's `src/` directory. The main motivation for this package was to aid in finding all functions that might trigger garbage collection by directly or indirectly calling `jl_gc_collect`; however, the package has broader uses.
- [Lens.jl](https://github.com/zenna/Lens.jl) : A simple Julia library to inspect the runtime behaviour of your programs, with minimal interference to the program itself.
- [LRUCache.jl](https://github.com/JuliaCollections/LRUCache.jl) : An implementation of a Least Recently Used (LRU) Cache.
- [ProfileSVG.jl](https://github.com/kimikage/ProfileSVG.jl) : Write flame graphs to SVG format and explore them interactively in Jupyter, Pluto, etc.
- [ProfileView.jl](https://github.com/timholy/ProfileView.jl) : Visualization of Julia profiling data
- [StatProfilerHTML.jl](https://github.com/tkluck/StatProfilerHTML.jl) : Show Julia profiling data in an explorable HTML page.

## Polymorphism amd multiple dispatch

**Resources**

- [Wikipedia: Polymorphism](https://en.wikipedia.org/wiki/Category:Polymorphism_(computer_science)) and [Holy Traits pattern](https://ahsmart.com/pub/holy-traits-design-patterns-and-best-practice-book.html).
- [The Design Impact of Multiple Dispatch](http://nbviewer.jupyter.org/gist/StefanKarpinski/b8fe9dbb36c1427b9f22) presented by StefanKarpinski at Strange Loop on 19-Sep-2013.
- [JuliaCon 2019: The Unreasonable Effectiveness of Multiple Dispatch by Stefan Karpinski](https://youtu.be/kc9HwsxE1OY)

**Packages**

- [BinaryTraits.jl](https://github.com/tk3369/BinaryTraits.jl) : easy-to-use trait library with formal interface specification support.
- [SimpleTraits.jl](https://github.com/mauro3/SimpleTraits.jl) : Simple Traits for Julia.
- [WhereTraits.jl](https://github.com/schlichtanders/WhereTraits.jl) : This package exports one powerful macro @traits with which you can extend Julia's where syntax.
- [ValSplit.jl](https://github.com/ztangent/ValSplit.jl) : Compile away dynamic dispatch on Val-typed arguments via value-splitting.
