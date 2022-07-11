# Development tools

Julia Developement tools, compilers, debuggers, [DevOps](https://en.wikipedia.org/wiki/DevOps)

**Organizations**

- [Julia debug](https://github.com/JuliaDebug)
- [Julia editor support](https://github.com/JuliaEditorSupport)
- [Julia packaging](https://github.com/JuliaPackaging)

## Static analysis

- [JET.jl](https://github.com/aviatesk/JET.jl) : experimental code analyzer for Julia.
- [Lint.jl](https://github.com/tonyhffong/Lint.jl) : A lint tool to hunt for imperfections and dodgy structures that could be improved for Julia code.

## Style Guidelines

[Official Julia style guide](https://docs.julialang.org/en/v1/manual/style-guide/)

- [Aqua.jl](https://github.com/JuliaTesting/Aqua.jl) : Auto QUality Assurance (automated checks) for Julia packages.
- [BlueStyle](https://github.com/invenia/BlueStyle) : A Julia style guide that lives in a blue world.
- [YASGuide](https://github.com/jrevels/YASGuide) : Yet Another Style Guide For Julia.

## Developing Julia packages

- [Compat.jl](https://github.com/JuliaLang/Compat.jl) : A package for cross-version compatibility between old Julia and the new - takes care of syntax breakage and provides compatibility constructs that will work in both versions without warnings.
- [FromFile.jl](https://github.com/Roger-luo/FromFile.jl) : providing a macro `@from` importing objects from files without having to `include` repeatedly.
- [Kip.jl](https://github.com/jkroso/Kip.jl) : An Python-like, alternative module system for Julia.
- [LocalRegistry.jl](https://github.com/GunnarFarneback/LocalRegistry.jl) : Create and maintain local package registries for Julia packages.
- [PkgCite.jl](https://github.com/SebastianM-C/PkgCite.jl) : prints a sentence with the citations for all the packages used in the current environment and will automatically copy it to the clipboard.
- [PkgSkeleton.jl][] : Generate Julia package skeletons using a simple template system.
- [PkgTemplates.jl][] : Create new Julia packages, the easy way. Include templaye files for GitHub / GitLab CI.
- [PkgUtils.jl](https://github.com/arnavs/PkgUtils.jl) by @arnavs : Some small utilities to help with Julia packages
- [Reexport.jl](https://github.com/simonster/Reexport.jl) : Julia macro for re-exporting one module from another.
- [Registrator.jl](https://github.com/JuliaComputing/Registrator.jl) : Julia [package](https://pkg.julialang.org/) registration bot.
- [Requires.jl](https://github.com/JuliaPackaging/Requires.jl) : Lazy code loading for Julia.
- [VersionParsing.jl](https://github.com/JuliaInterop/VersionParsing.jl) : flexible VersionNumber parsing in Julia.

[PkgTemplates.jl]: https://github.com/invenia/PkgTemplates.jl
[PkgSkeleton.jl]: https://github.com/tpapp/PkgSkeleton.jl

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏗️ [PkgDev.jl](https://github.com/JuliaLang/PkgDev.jl) : Julia Package Development Kit.

</details>

### Prebuilt Binaries

**Resources**

- [Julia Packaging](https://github.com/JuliaPackaging) team
- [Yggdrasil][] binary repository.
- [Artifacts](https://pkgdocs.julialang.org/v1/artifacts/) in Julia packaging system.

---

**Packages**

- [BinaryBuilder.jl](https://github.com/JuliaPackaging/BinaryBuilder.jl) : Binary Dependency Builder for Julia.
- [BinaryProvider.jl](https://github.com/JuliaPackaging/BinaryProvider.jl) : A reliable binary provider for Julia.
- [BinDeps.jl](https://github.com/JuliaLang/BinDeps.jl) : Tool for building binary dependencies for Julia modules.
- [RunBinary.jl](https://gitlab.com/aplavin/RunBinary.jl) : running binaries from the [Yggdrasil][] repo.

[Yggdrasil]: https://github.com/JuliaPackaging/Yggdrasil

### Compilers

- [Clang.jl](https://github.com/ihnorton/Clang.jl) : Julia interface to libclang and C wrapper generator.
- [llvm-cbe](https://github.com/JuliaComputingOSS/llvm-cbe) : A resurrected LLVM C Backend, with improvements for Julia.
- [PackageCompiler.jl](https://github.com/JuliaLang/PackageCompiler.jl) : Compile your Julia enviironment into a system image or a standalone binary.
- [SnappyBuilder](https://github.com/davidanthoff/SnappyBuilder) : BinaryBuilder for `libsnappy` to build Julia ssnap package.

### Julia developement helpers

- [FemtoCleaner.jl](https://github.com/JuliaComputing/FemtoCleaner.jl) : The [FemtoCleaner](https://github.com/apps/femtocleaner) app cleans your julia projects by upgrading deprecated syntax, removing version compatibility workarounds and anything else that has a unique upgrade path. This app exist to smooth the transition from Julia version 0.6 to 0.7(1.0+).

## Test-driven develpment (TDD)

**Resources**

- [Unittest in Julia](https://docs.julialang.org/en/v1/stdlib/Test/)

**Packages**

- [Coverage.jl](https://github.com/JuliaCI/Coverage.jl) : tracking code testing coverage and memory usage and optionally upload them to online services like Coveralls or Codecov. Its base library is [CoverageBase.jl](https://github.com/JuliaCI/CoverageBase.jl).
- [Jive.jl](https://github.com/wookay/Jive.jl) : running test in parallel. It also supports watch folder function.
- [MockAWS.jl](https://github.com/JuliaCloud/MockAWS.jl) : patch functions for testing all AWS services.
- [Mocking.jl](https://github.com/invenia/Mocking.jl) : allowing temporary overwriting of Julia methods for testing purposes.
- [TestEnv.jl](https://github.com/JuliaTesting/TestEnv.jl) : Activate your test enviroment, so you can use your test dependencies in the REPL.
- [UnitTestDesign.jl](https://github.com/adolgert/UnitTestDesign.jl) : chooses effiennt combinations functional arguments to maximize test coverage.
- [Watcher.jl](https://github.com/rened/Watcher.jl) : auto-run unit tests every time a file gets saved.
- [SafeTestsets.jl](https://github.com/YingboMa/SafeTestsets.jl) : `@safetestset` puts `@testset` into a module to reduce global side effects.

### Logging

See aslo the built-in [Julia logging](https://docs.julialang.org/en/v1/stdlib/Logging/) facilities.

- [ProgressLogging.jl](https://github.com/JuliaLogging/ProgressLogging.jl) : a package for defining progress logs.


## Benchmarking and Regression Testing

**Resources**

- [Julia Microbenchmarks against other programming languages](https://julialang.org/benchmarks/)

**Packages**

- [BenchmarkTools.jl](https://github.com/JuliaCI/BenchmarkTools.jl) : A benchmarking framework for the Julia language.
- [ConicBenchmarkUtilities.jl](https://github.com/JuliaOpt/ConicBenchmarkUtilities.jl) : Julia utilities for the conic benchmark format for mathematical optimization.
- [CPUTime.jl](https://github.com/schmrlng/CPUTime.jl) : A module for CPU timing.
- [DataBench.jl](https://github.com/xiaodaigh/DataBench.jl) : A package to benchmark data manipulation in Julia vs `R data.table`.
- [PkgBenchmark.jl](https://github.com/JuliaCI/PkgBenchmark.jl) : Easy benchmark tracking for packages
- [PkgEval.jl](https://github.com/JuliaCI/PkgEval.jl) : Evaluate Julia packages for a range of Julia versions.
- [PkgJogger.jl](https://github.com/awadell1/PkgJogger.jl) : a benchmarking framework for Julia built on `BenchmarkTools.jl`, providing simple benchmark script loading and revision (by `Revise.jl`). It also enables continuous benchmarking.
- [ProfileSVG.jl](https://github.com/kimikage/ProfileSVG.jl) : Write flame graphs to SVG format and explore them interactively in Jupyter, Pluto, etc.
- [ProfileView.jl](https://github.com/timholy/ProfileView.jl) : Visualization of Julia profiling data
- [SimplexBenchmarks](https://github.com/mlubin/SimplexBenchmarks) : Benchmarks comparing individual operations of the Simplex method for linear programming in Julia and other languages. Uses modified version of jlSimplex to generate data from real instances.
- [StatProfilerHTML.jl](https://github.com/tkluck/StatProfilerHTML.jl) : Show Julia profiling data in an explorable HTML page.
- [TimerOutputs.jl](https://github.com/KristofferC/TimerOutputs.jl) : Formatted output of timed sections in julia.
- [VisualRegressionTests.jl](https://github.com/JuliaPlots/VisualRegressionTests.jl) : Automated integrated regression tests for graphics libraries.

## Debugger

- [Debugger.jl](https://github.com/JuliaDebug/Debugger.jl) : Julia debugger using the `@enter` macro.
- [Ghost.jl](https://github.com/dfdx/Ghost.jl) : a code tracer for the Julia programming language. It lets you trace the function execution, recording all primitive operations onto a linearized tape.
- [Infiltrator.jl](https://github.com/JuliaDebug/Infiltrator.jl) : `@infiltrate` macro sets a "breakpoint" in a local context. All code is completely compiled.
- [JuliaInterpreter.jl](https://github.com/JuliaDebug/JuliaInterpreter.jl) : Interpreter for Julia code.
- [Rebugger.jl](https://github.com/timholy/Rebugger.jl) : An expression-level debugger for Julia, sans the ability to interact with or manipulate call stacks (see [Gallium](https://github.com/Keno/Gallium.jl)), but it can trace execution via the manipulation of Julia expressions.
- [Suppressor.jl](https://github.com/Ismael-VC/Suppressor.jl) :  Julia macros for suppressing output (STDOUT), warnings (STDERR) or both streams at the same time.
- [ToggleableAsserts.jl](https://github.com/MasonProtter/ToggleableAsserts.jl) : Assertions that can be turned on or off with a switch, without runtime penalty when they're off.
- [Traceur.jl](https://github.com/MikeInnes/Traceur.jl) : codified version of the [Julia performance tips](https://docs.julialang.org/en/v1/manual/performance-tips/). You run your code, it tells you about any obvious performance traps.

## Documentation and report generation

[Julia docstrings](https://docs.julialang.org/en/v1/manual/documentation/)

- [Books.jl](https://github.com/JuliaBooks/Books.jl) : generate books (or dashboards) in pdf/HTML/docx with embedded Julia output by pandoc document processor. Currently, this package is used to write the [Julia Data Science book](https://github.com/JuliaDataScience/JuliaDataScience).
- [CommonMark.jl](https://github.com/MichaelHatherly/CommonMark.jl) : A CommonMark-compliant parser for Julia.
- [DocStringExtensions.jl](https://github.com/JuliaDocs/DocStringExtensions.jl) : Extensions for Julia's docsystem.
- [Documenter.jl](https://github.com/JuliaDocs/Documenter.jl) : Official documentation generator for Julia.
- [Literate.jl](https://github.com/fredrikekre/Literate.jl) : literate programming in Julia.
- [Remark.jl](https://github.com/piever/Remark.jl) : A Julia package to create presentations from markdown using Remark.
- [sphinx-julia](https://github.com/bastikr/sphinx-julia) : Documenting Julia projects with Sphinx.
- [Weave.jl](https://github.com/JunoLab/Weave.jl) : A scientific report generator/literate programming tool for Julia based on Pweave and resembles Knitr and Sweave.

## Integrated development environment (IDE)

[Julia editor suport](https://github.com/JuliaEditorSupport) organization.

- [jEdit-julia](https://github.com/tuckerkevin/jedit-julia) : A [jEdit](http://jedit.org/) mode for Julia.
- [Julia VSCode](https://www.julia-vscode.org/) : A powerful, free IDE for the Julia language.
- [Julia.tmbundle](https://github.com/JuliaLang/Julia.tmbundle) : Julia language support for TextMate 2 (and Sublime Text).
- [Liclipse](https://www.liclipse.com/) : LiClipse, Eclipse plus some customizations, supports Julia.
- [Reminisce](https://github.com/JuliaIDE/Reminisce) : Sublime-style saving of tabs and content for Light Table.
- [JuliaMono](https://github.com/cormullion/juliamono) : A monospaced font for Julia with unicode characters and ligatures.

### Atom

> The development is shifted to Julia VSCode. Juno (Julia in Atom) is currently in maintenance mode.

- [Atom.jl](https://github.com/JunoLab/Atom.jl) : Julia Client for Atom. Curently in maintenance mode.
- [atom-language-julia](https://github.com/JuliaLang/atom-language-julia) : A Julia language support package for the Atom editor.
- [atom-julia-client](https://github.com/JunoLab/atom-julia-client) : Julia Eval in Atom.

### Emacs

- [emacs-ess-julia.el](https://github.com/emacs-ess/ESS/blob/master/lisp/ess-julia.el) : ESS support for julia language, includes font-lock, indentation, sending code to sub-process, interactive documentation, imenu, completion and eldoc. Also see its [Installation instructions for Julia](https://github.com/emacs-ess/ESS/wiki/Julia)
- [julia-emacs](https://github.com/JuliaEditorSupport/julia-emacs) : Julia support in Emacs.
- [julia-repl](https://github.com/tpapp/julia-repl) : Run an interior Julia REPL in a terminal inside Emacs.

### Vim

- [Julia-Vim](https://github.com/JuliaLang/julia-vim).
- [Neovim.jl](https://github.com/bfredl/Neovim.jl) by @bfredl : Neovim client for Julia.
- [vim-notebook](https://github.com/baruchel/vim-notebook) : Vim users can use Julia from the `vim-notebook` plugin.

### Jupyter

[Jupyter](https://github.com/jupyter)


- [IJulia.jl](https://github.com/JuliaLang/IJulia.jl) : Julia kernel for Jupyter. How to create a [Custom IJulia Widget](https://nbviewer.org/urls/gist.githubusercontent.com/avrahamruderman/116845471f0d79942aff/raw/fb1f659e635f4585ebb449aa2519deffd15aba31/writing-custom-ijulia-widgets.ipynb)
- [Interact.jl](https://github.com/JuliaGizmos/Interact.jl) : Library for interactive widgets in IJulia.
- [IPython.jl](https://github.com/tkf/IPython.jl) : Launch IPython in Julia.
- [NBInclude.jl](https://github.com/stevengj/NBInclude.jl) : Import code from IJulia Jupyter notebooks into Julia programs.
- [Sublime-IJulia](https://github.com/quinnj/Sublime-IJulia) : is an IJulia Frontend to run julia from within Sublime Text-3 through the IJulia backend.


### Web IDE

[Wikipedia: web IDE](https://en.wikipedia.org/wiki/Web_integrated_development_environment)

**Resources**
- [Google colab Julia notebook](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_for_Pythonistas.ipynb)
- [Julia Hub](https://juliahub.com/ui/index.html)
- [Julia on the SageMath cloud server](https://cloud.sagemath.com)
- [Repl.it](https://replit.com/)
- [Nextjournal](https://nextjournal.com/)
- [CodeBunk](https://codebunk.com) supports Julia for collaborative screen-sharing on the cloud.

---

**Packages**

- [CodeTools.jl](https://github.com/JunoLab/CodeTools.jl) : A collection of tools for handling Julia code (evaluation, autocompletion etc.), designed to be used as a backend library for IDE support.
- [DevTools.jl](https://github.com/JunoLab/DevTools.jl) : provides a couple of useful graphical tools for working with Julia, built on top of Blink.jl.
- [Hiccup.jl](https://github.com/JunoLab/Hiccup.jl) : A super-simple library designed to make making HTML easy in Julia. It's heavily inspired by Clojure's Hiccup DSL.
- [LanguageServer.jl](https://github.com/julia-vscode/LanguageServer.jl) : An implementation of the Microsoft Language Server Protocol for the julia language.
- [LNR.jl](https://github.com/JunoLab/LNR.jl) : Line numbering reader.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Media.jl](https://github.com/JunoLab/Media.jl) : A display system which enables the user handle multiple input/output devices and decide what media types get displayed where. (No `Project.toml`)

</details>

## Shell scripting

[Shell scripting](https://en.wikipedia.org/wiki/Shell_script)

[Administrative scripting with Julia](https://github.com/ninjaaron/administrative-scripting-with-julia) : A guide for writing shell scripts in Julia.

- [Homebrew.jl](https://github.com/JuliaLang/Homebrew.jl/) : OSX Binary dependency provider for Julia.
- [LibALPM.jl](https://github.com/yuyichao/LibALPM.jl) : Wrapper for libalpm, the ArchLinux package manager.
- [WinRPM.jl](https://github.com/JuliaLang/WinRPM.jl) : RPM-md processing library to crosscompile code for Windows.

## GUI

- [Blink.jl](https://github.com/JuliaGizmos/Blink.jl) : Julia wrapper around [Electron](https://electronjs.org/).
- [Electron.jl](https://github.com/davidanthoff/Electron.jl) : Julia wrapper for [Electron](https://electronjs.org/) with a more minimalistic feature set than `Blink.jl`.
- [Tk.jl](https://github.com/JuliaGraphics/Tk.jl) : The Julia interface for the Tk windowing toolkit.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Escher.jl](https://github.com/JuliaGizmos/Escher.jl) : Composable UIs in Julia.

</details>

### Qt

- [QML.jl](https://github.com/barche/QML.jl) : Small example for starting an interface to Qt5 QML.

### GTK

- [Gtk.jl](https://github.com/JuliaLang/Gtk.jl) : Julia interface to the GTK windowing toolkit.
- [GtkApps.jl](https://github.com/tknopp/GtkApps.jl) : GTK Apps by @tknopp.

## Continuous integration (CI) providers

[PkgTemplates.jl][] and [PkgSkeleton.jl][] could generate the CI/CD configuration files.

### Travis

Unfortunately, [Travis does not love opensource anymore](https://www.theregister.com/2020/11/02/travis_ci_pricng/).

### Gitlab-CI

- [GitlabJuliaDemo.jl](https://gitlab.com/tkpapp/GitlabJuliaDemo.jl) : A minimal example for setting up CI with Julia on Gitlab. The [blog post](https://tpapp.github.io/post/julia-ci-gitlab/) describing how a Julia package repo in Gitlab can be setup with continuous integration and coverage summary. A sample CI file `.gitlab-ci.yml` is [here](https://gitlab.com/tkpapp/GitlabJuliaDemo.jl/-/blob/master/.gitlab-ci.yml).

### GitHub

[GitHub actions for Julia](https://github.com/julia-actions). A sample CI file can be accessed [here](https://github.com/tpapp/PkgSkeleton.jl/blob/master/.github/workflows/CI.yml).

- [setup-julia](https://github.com/julia-actions/setup-julia) : downloading a specified version of Julia and adding it to PATH.
- [julia-buildpkg](https://github.com/julia-actions/julia-buildpkg)
- [julia-runtest](https://github.com/julia-actions/julia-runtest)
- [julia-processcoverage](https://github.com/julia-actions/julia-processcoverage)
- [CompatHelper workflow](https://github.com/JuliaRegistries/CompatHelper.jl/blob/master/.github/workflows/CompatHelper.yml)

## Containers and Virtualization

[Virtualization](https://en.wikipedia.org/wiki/Category:Virtualization_software)

- [Julia docker image](https://hub.docker.com/_/julia) and the packaging [`DOCKERFILE`](https://github.com/docker-library/julia).
- [Kuber.jl](https://github.com/JuliaComputing/Kuber.jl) : A Julia Kubernetes Client.

## Sandbox

- [Playground.jl](https://github.com/Rory-Finnegan/Playground.jl) : A Julia-lang environment builder (like python's virtualenv) package to create Julia sandboxes, similar to python virtual environments.

## Resources

- [Awesome devops](https://github.com/wmariuss/awesome-devops)
- [cache.julialang.org](https://github.com/staticfloat/cache.julialang.org) : JuliaLang binary caching infrastructure.
- [Devops Weekly](https://www.devopsweekly.com/) email subscription and the [public archive](https://devopsweeklyarchive.com/).
- [julia-buildbot](https://github.com/JuliaCI/julia-buildbot) : Buildbot configuration for [build.julialang.org](https://build.julialang.org/).
- [JuliaHub](https://juliahub.com/ui/Home)
- [General registry](https://github.com/JuliaRegistries/General) : The official registry of general Julia packages.
