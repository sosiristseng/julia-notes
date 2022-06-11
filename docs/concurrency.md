# Concurrency

- Julia HPC and Cluster computing.
- Distributed Computing and Grid computing.
- Cloud computing
- Parallel computing
- Hardware architectures (ARM, CUDA, GPU, MIPS) anb compute kernels

**Organizations**

- [Julia Parallel](https://github.com/JuliaParallel)
- [Julia Folds](https://github.com/JuliaFolds)
- [Julia Cloud](https://github.com/JuliaCloud)

---

## General Concurrency Packages

- [Actors.jl](https://github.com/JuliaActors/Actors.jl) : Concurrent computing in Julia based on the [Actor Model](https://en.wikipedia.org/wiki/Actor_model).
- [FLoops.jl](https://github.com/JuliaFolds/FLoops.jl): the macro `@floop` for a fast generic iteration over complex collections.
- [Folds.jl](https://github.com/JuliaFolds/Folds.jl) : A unified interface for sequential, threaded, and distributed folds. The [docs](https://juliafolds.github.io/Folds.jl/stable/) list what functions it supports.
- [TiledIteration.jl](https://github.com/JuliaArrays/TiledIteration.jl) : Julia package to facilitate writing mulithreaded, multidimensional, cache-efficient code.

## APIs and bindings

- [AppleAccelerate.jl](https://github.com/JuliaMath/AppleAccelerate.jl) : Julia interface to OS X's Accelerate framework.
- [ArrayFire.jl](https://github.com/JuliaGPU/ArrayFire.jl) : Julia Wrapper for the [ArrayFire](https://arrayfire.com/) library.
- [Elly.jl](https://github.com/JuliaParallel/Elly.jl) : [Hadoop](https://hadoop.apache.org/) HDFS and Yarn client.
- [Hwloc.jl](https://github.com/JuliaParallel/Hwloc.jl) : Wrapper to the [hwloc library](https://www.open-mpi.org/projects/hwloc/) to provide a portable abstraction (across OS, versions, architectures, ...) of the hierarchical topology of modern architectures, including NUMA memory nodes, sockets, shared caches, cores and simultaneous multithreading.
- [julia-slurm-example](https://github.com/magerton/julia-slurm-example) : Simple example scripts for running Julia on a SLURM.
- [MPI.jl](https://github.com/JuliaParallel/MPI.jl) : [MPI](https://www.mpi-forum.org/) wrappers for Julia.

## Cloud computing

- [AWS.jl](https://github.com/JuliaCloud/AWS.jl) : supports the EC2 and S3 API's, letting you start and stop EC2 instances dynamically.
- [AWSCore.jl](https://github.com/JuliaCloud/AWSCore.jl) : [Amazon Web Services](https://aws.amazon.com/) Core Functions and Types.
- [AWSS3.jl](https://github.com/JuliaCloud/AWSS3.jl) : AWS S3 Simple Storage Service interface for Julia.
- [GoogleCloud.jl](https://github.com/JuliaCloud/GoogleCloud.jl) : Google Cloud APIs for Julia.
- [Kuber.jl](https://github.com/JuliaComputing/Kuber.jl) : Julia Kubernetes Client.

## SIMD Computing

- [Wikipedia: SIMD Computing](https://en.wikipedia.org/wiki/Category:SIMD_computing).
- [Julia docs: `@simd`](https://docs.julialang.org/en/v1/base/base/#Base.SimdLoop.@simd) macro.

**Packages**

- [LoopVectorization.jl](https://github.com/JuliaSIMD/LoopVectorization.jl) : `@turbo` macro for vectorizing loops.
- [SIMD.jl](https://github.com/eschnett/SIMD.jl) : Explicit SIMD vector operations for Julia.

## Multi-Threading

- [KissThreading.jl](https://github.com/mohamed82008/KissThreading.jl) : Simple patterns supporting working with threads in Julia.
- [ThreadsX.jl](https://github.com/tkf/ThreadsX.jl) : Parallelized Base functions.

## Multiprocessing and Distributed Computing

- [Wikipedia: Distributed Computing](https://en.wikipedia.org/wiki/Category:Distributed_computing) across multiple compute nodes.
- [Wikipedia: Job Scheduler](https://en.wikipedia.org/wiki/Job_scheduler)
- [Julia at scale](https://discourse.julialang.org/c/domain/parallel/34) topic on discourse.

**Packages**

- [MPI.jl](https://github.com/JuliaParallel/MPI.jl):  Julia interface to the Message Passing Interface ([MPI](https://www.mpi-forum.org/))
- [Dagger.jl](https://github.com/JuliaParallel/Dagger.jl) : A framework for out-of-core and parallel computation and hierarchical Scheduling of DAG Structured Computations. Similar to [`dask`](https://dask.org/) in Python.
- [DistributedArrays.jl](https://github.com/JuliaParallel/DistributedArrays.jl) : A task persistency mechanism based on hash-graphs for Dispatcher.jl.
- [ClusterManagers.jl](https://github.com/JuliaLang/ClusterManagers.jl) : Support for different clustering technologies.
- [DispatcherCache.jl](https://github.com/zgornel/DispatcherCache.jl) : Tool for building and executing a computation graph given a series of dependent operations.
- [FunHPC.jl](https://github.com/eschnett/FunHPC.jl) : Functional High-Performance Computing - A high-level API for distributed computing, implemented on top of MPI. [Bitbucket](https://bitbucket.org/eschnett/funhpc.jl) mirror.
- [HPAT.jl](https://github.com/IntelLabs/HPAT.jl) : High Performance Analytics Toolkit (HPAT) is a Julia-based framework for big data analytics on clusters.
- [JuliaMPIMonteCarlo.jl](https://github.com/mcreel/JuliaMPIMonteCarlo.jl) : Illustrative examples using Julia and MPI to do Markov Chain Monte Carlo (MCMC) methods.
- [MessageUtils.jl](https://github.com/JuliaParallel/MessageUtils.jl) : A collection of utilities for messaging.
- [MPIArrays.jl](https://github.com/barche/MPIArrays.jl) : Distributed arrays based on MPI onesided communication.
- [ParallelDataTransfer.jl](https://github.com/ChrisRackauckas/ParallelDataTransfer.jl) : A bunch of helper functions for transferring data between worker processes.
- [Persist.jl](https://github.com/eschnett/Persist.jl) : The package Persist allows running jobs independent of the Julia shell.
- [Schedulers.jl](https://github.com/ChevronETC/Schedulers.jl) : It provides elastic and fault tolerant parallel map and parallel map reduce methods. The primary feature that distinguishes Schedulers parallel map method from Julia's `Distributed.pmap` is elasticity where the cluster is permitted to dynamically grow/shrink.

## GPU computing

[Wikipedia: GPGPU](https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units)

**Resources**

- Blog post on [Compiling Julia for NVIDIA GPUs](http://blog.maleadt.net/2015/01/15/julia-cuda/)
- Sample notebooks for: [GPU Julia](https://nbviewer.org/7436359), and [GPU Transpose](https://nbviewer.org/gist/jakebolewski/7436439).
- Blog post on [High-Performance GPU Computing](https://devblogs.nvidia.com/parallelforall/gpu-computing-julia-programming-language/#more-8555) in the Julia Programming Language.

**Packages**

- [AMDGPU.jl](https://github.com/JuliaGPU/AMDGPU.jl) : AMD GPU (ROCm) programming in Julia.
- [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl) : CUDA programming in Julia. [JuliaCon 2021 video](https://youtu.be/fw0R5G8pB0U)
- [CVortex.jl](https://github.com/hjabird/CVortex.jl) : Julia wrapper for [cvortex](https://github.com/hjabird/cvortex) GPU accelerated vortex filament and vortex particle methods.
- [CuCountMap.jl](https://github.com/xiaodaigh/CuCountMap.jl) : Fast `StatsBase.countmap` for small types on the GPU via `CUDA.jl`
- [FoldsCUDA.jl](https://github.com/JuliaFolds/FoldsCUDA.jl): provides `Transducers.jl`-compatible fold (reduce) implemented using `CUDA.jl`. This brings the transducers and reducing function combinators implemented in Transducers.jl to GPU. Furthermore, using FLoops.jl, you can write parallel for loops that run on GPU.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [MXNet.jl](https://github.com/dmlc/MXNet.jl/tree/stable) : The dmlc/mxnet Julia package that brings flexible and efficient GPU computing and state-of-art deep learning to Julia. `MXNet.jl` is a part of Apache [MXNet](https://github.com/apache/incubator-mxnet) project. (No `Project.toml`)
- 🏚️ [OpenCL.jl](https://github.com/JuliaGPU/OpenCL.jl) : OpenCL 1.2 Julia bindings - a cross platform parallel computation API for programming parallel devices, with implementations from AMD, Nvidia, Intel, and others, similar in scope to PyOpenCL.

</details>

## Resources

- [Julia manual for parallel computing](https://docs.julialang.org/en/v1/manual/parallel-computing/)
- [Wikipedia: Concurrency](https://en.wikipedia.org/wiki/Concurrency_%28computer_science%29)
- [Wikipedia: Parallel Computing](https://en.wikipedia.org/wiki/Category:Parallel_computing)
