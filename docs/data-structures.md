# Data Structures

**Organizations**

- [Julia Collections](https://github.com/JuliaCollections)
- [Julia ArbTypes](https://github.com/JuliaArbTypes)

## General data structures

- [Air.jl](https://github.com/noahbenson/Air.jl) : Light-weight functional collections and utilities for Julia.
- [DataStructures.jl](https://github.com/JuliaCollections/DataStructures.jl) : Julia implementation of Data structures.
- [ErrorTypes.jl](https://github.com/jakobnissen/ErrorTypes.jl) : A simple implementation of Rust-like error handling in Julia.
- [FunctionalCollections.jl](https://github.com/JuliaCollections/FunctionalCollections.jl) : Functional and and persistent data structures for Julia.
- [FunctionalData.jl](https://github.com/rened/FunctionalData.jl) : Functional, efficient data manipulation framework.
- [MUtils.jl](https://github.com/JuliaParallel/MessageUtils.jl) : A collection of utilities for messaging, `channels()`, `tspaces()`, `kvspaces()` etc.
- [ResultTypes.jl](https://github.com/iamed2/ResultTypes.jl) : A Result type for returning a value or an error in a type-stable manner without throwing an exception.
- [TypeSortedCollections.jl](https://github.com/tkoolen/TypeSortedCollections.jl) : It provides the TypeSortedCollection type, which can be used to store type-heterogeneous data in a way that allows operations on the data to be performed in a type-stable manner.

## Text / string data type

- [FixedSizeStrings.jl](https://github.com/JuliaComputing/FixedSizeStrings.jl) : A type for efficiently storing short strings of known size.
- [Format.jl](https://github.com/JuliaString/Format.jl) : This Julia package provides C and Python-style types and functions formatting support.
- [Formatting.jl](https://github.com/JuliaIO/Formatting.jl) : A Julia package to provide Python-like formatting support.
- [LaTeXStrings.jl](https://github.com/stevengj/LaTeXStrings.jl) : This is a small package to make it easier to type LaTeX equations in string literals in the Julia language.
- [ShortStrings.jl](https://github.com/JuliaString/ShortStrings.jl) : A fast and efficient string format implementation for storing strings of size less than 15 bytes.
- [StringDistances.jl](https://github.com/matthieugomez/StringDistances.jl) : String Distances in Julia.
- [StringLiterals.jl](https://github.com/JuliaString/StringLiterals.jl) : Implement improved string literals with Swift-style syntax for interpolation, hex, & unicode characters, plus C & Python style formatting and Unicode, HTML, LaTeX, and Emoji entities.
- [VersionParsing.jl](https://github.com/JuliaInterop/VersionParsing.jl) : flexible VersionNumber parsing in Julia.
- [WeakRefStrings.jl](https://github.com/JuliaData/WeakRefStrings.jl) : a minimal String type for Julia that allows for efficient string representation and transfer.

### i18n-L10n and unicode tools

- [Gettext.jl](https://github.com/Julia-i18n/Gettext.jl) : An interface to the [gettext](http://www.gnu.org/software/gettext/manual/html_node/index.html) internationalization/translation interface.
- [ICU.jl](https://github.com/JuliaStrings/ICU.jl) : Julia wrapper for the International Components for Unicode (ICU) library.
- [LegacyStrings.jl](https://github.com/JuliaArchive/LegacyStrings.jl) : The LegacyStrings package provides compatibility string types from Julia 0.5 (and earlier).

## Graph data types

See [Graph Theory](./graph.md#graph-data-types) section.

## Numeric data types

- [ArbNumerics.jl](https://github.com/JeffreySarnoff/ArbNumerics.jl) : extended precision math, accurate and performant
- [BFloat16s.jl](https://github.com/JuliaMath/BFloat16s.jl) : This package defines the [BFloat16 data type](https://en.wikipedia.org/wiki/Bfloat16_floating-point_format). The only currently available hardware implementation of this datatype are Google's [Cloud TPUs](https://en.wikipedia.org/wiki/Tensor_processing_unit).
- [BitIntegers.jl](https://github.com/rfourquet/BitIntegers.jl) : This package implements fixed-width integer types similar to standard builtin-ones like Int or UInt128.
- [ClosedIntervals.jl](https://github.com/scheinerman/ClosedIntervals.jl) : Closed intervals of the form [a,b].
- [CustomUnitRanges.jl](https://github.com/JuliaArrays/CustomUnitRanges.jl) : Package-specific AbstractUnitRange types for julia.
- [DecFP.jl](https://github.com/JuliaMath/DecFP.jl) : The package provides 32-bit, 64-bit, and 128-bit binary-encoded decimal floating-point types following the IEEE 754-2008, implemented as a wrapper around the (BSD-licensed) [Intel Decimal Floating-Point Math Library](https://software.intel.com/en-us/articles/intel-decimal-floating-point-math-library).
- [Decimals.jl](https://github.com/JuliaMath/Decimals.jl) : Pure Julia decimal arithmetic library.
- [DoubleFloats.jl](https://github.com/JuliaMath/DoubleFloats.jl) : Math with 85- accurate bits.
- [FixedPointNumbers.jl](https://github.com/JuliaMath/FixedPointNumbers.jl) : This library exports fixed-point number types. A fixed-point number represents a fractional, or non-integral, number. In contrast with the more widely known floating-point numbers, fixed-point numbers have a fixed number of digits (bits) after the decimal (radix) point. They are effectively integers scaled by a constant factor.
- [Infinity.jl](https://github.com/cjdoris/Infinity.jl) : Representation of infinity in Julia.
- [LogarithmicNumbers.jl](https://github.com/cjdoris/LogarithmicNumbers.jl): Provides the signed `ULogarithmic` and unsigned `Logarithmic` types for representing real numbers on a logarithmic scale.
- [Measurements.jl](https://github.com/JuliaPhysics/Measurements.jl) : Error propagation calculator and library. It supports real and complex numbers with uncertainty, arbitrary precision calculations, and operations with arrays.
- [MonteCarloMeasurements.jl](https://github.com/baggepinnen/MonteCarloMeasurements.jl) : Error propagation using Monte-Carlo simulation. Similar to Measurements.jl, but more accurate for highly nonlinear functions at the expense of longer execution time.
- [Measures.jl](https://github.com/JuliaGraphics/Measures.jl) : Unified measure and coordinates types.
- [Quaternions.jl](https://github.com/JuliaGeometry/Quaternions.jl) : Quaternions, octonions and dual-quaternions.
- [Quaternions.jl](https://github.com/peakbook/Quaternions.jl) by @peakbook : Quaternion for Julia Language.
- [Ratios.jl](https://github.com/timholy/Ratios.jl) : Faster Rational-like types for Julia.
- [Unitful.jl](https://github.com/PainterQubits/Unitful.jl) : A Julia package for physical units.

## Array types

See also [math | Linear Algebra | Array Data structures](./math.md#array-data-structures)

## Composite Data Types

[Wikipedia: Composite Data Types](https://en.wikipedia.org/wiki/Category:Composite_data_types)

See also: [`Base.@kwdef`](https://discourse.julialang.org/t/what-does-kwdef-do/51973) for a concise struct construction in the Julia base.

---

- [Accessors.jl](https://github.com/JuliaObjects/Accessors.jl) : updating immutable data simple. It is the successor of `Setfield.jl`.
- [Bijections.jl](https://github.com/scheinerman/Bijections.jl) : Bijection datatype for Julia that blocks assigning the same value to two different keys.
- [ConcreteStructs.jl](https://github.com/jonniedie/ConcreteStructs.jl) : `@concrete` can be used to make non-concrete structs concrete without the boilerplate of adding type parameters.
- [Dictionaries.jl](https://github.com/andyferris/Dictionaries.jl) : An alternative interface for dictionaries in Julia, for improved productivity and performance.
- [DispatchedTuples.jl](https://github.com/charleskawczynski/DispatchedTuples.jl): `Dispatched Tuples` are like immutable dictionaries (so, they're technically more like NamedTuples) except that the keys are instances of types. Also, because DispatchedTuples are backed by tuples, they are GPU-friendly.
- [ExtractMacro.jl](https://github.com/carlobaldassi/ExtractMacro.jl) : Provides a convenience `@extract` macro to extract fields from composite types.
- [NamedTupleTools.jl](https://github.com/JeffreySarnoff/NamedTupleTools.jl) : utilities for working with NamedTuples.
- [Parameters.jl](https://github.com/mauro3/Parameters.jl) : Types with default field values, keyword constructors and (un-)pack macros.
- [Setfield.jl](https://github.com/jw3126/Setfield.jl) : Update deeply nested immutable structs.
- [SimpleTraits.jl](https://github.com/mauro3/SimpleTraits.jl) : Simple Traits for Julia
- [TypedDelegation.jl](https://github.com/JuliaArbTypes/TypedDelegation.jl) :  Use a Type's fields as operands for the type's operations and easily apply functions onto fields' values.
- [TypeParams.jl](https://github.com/synchronoustechnologies/TypeParams.jl) : keeping compile-time type information in `struct` for better performance.
- [Unpack.jl](https://github.com/mauro3/UnPack.jl) : `@unpack` some or all of the fields of a type, and `@pack`, in the case of mutable datatypes.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [SymDict.jl](https://github.com/JuliaCloud/SymDict.jl) : Convenience functions for dictionaries with Symbol keys. (No `Project.toml`). You can use `Dict(pairs(nt))` instead.

</details>

## Resources


- [Youtube: The State of the Type System](https://www.youtube.com/watch?v=Z2LtJUe1q8c) at JuliaCon 2017 by Jeff Bezanson
- [Youtube: The Unreasonable Effectiveness of Multiple Dispatch](https://youtu.be/kc9HwsxE1OY)  at JuliaCon 2019 by Stefan Karpinski
- [A more thorough look at Julia's **double colon** syntax](https://nbviewer.org/github/tlycken/IJulia-Notebooks/blob/master/A%20more%20thorough%20look%20at%20Julia%27s%20%22double%20colon%22%20syntax.ipynb)
