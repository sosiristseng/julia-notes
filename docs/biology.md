# Biology

> Bioinformatics, genomics, agriculture, food science, medicine, genetic engineering, etc., in Julia.

- [BioJulia](https://biojulia.net/) organization
- [Julia Health](https://juliahealth.org) organization

## Accessing biology databases

- [BioFetch.jl](https://github.com/BioJulia/BioFetch.jl) : Easily fetch biological sequences from online sources. Currently supports Entrez (NCBI) Nucleotide and Protein databases, as well as UniProt and Ensembl.
- [BioMedQuery.jl](https://github.com/JuliaHealth/BioMedQuery.jl) : Julia utilities to process and save results from BioMedical databases/APIs.
- [BioServices.jl](https://github.com/BioJulia/BioServices.jl) : Julia interface to APIs for various bio-related web services.
- [DailyMed.jl](https://github.com/wherrera10/DailyMed.jl) : Interface to the REST functions of the National Library of Medicine's DailyMed database.
- [PubChemCrawler.jl](https://github.com/JuliaHealth/PubChemCrawler.jl) : Utilities to programmatically query the PubChem database.
- [PubMedMiner.jl](https://github.com/JuliaHealth/PubMedMiner.jl) : Julia package for studying co-occurrences in PubMed articles.
- [RxNav.jl](https://github.com/wherrera10/RxNav.jl) : Julia interface to the National Library of Medicine's online pharmaceutical RxNav API.

## Bioinformatics and genomics

- [Ensemble.jl](https://github.com/farr/Ensemble.jl) : Stochastic samplers based on the "stretch move" for ensembles of walkers.
- [FastaIO.jl](https://github.com/carlobaldassi/FastaIO.jl) : Utilities to read/write FASTA format files in Julia.
- [MIToS.jl](https://github.com/diegozea/MIToS.jl) : Mutual Information Tools for protein Sequence analysis in Julia.
- [MMTF.jl](https://github.com/BioJulia/MMTF.jl) : The Macromolecular Transmission Format (MMTF) is a new compact binary format to transmit and store biomolecular structures for fast 3D visualization and analysis.
- [NormalizeQuantiles.jl](https://github.com/oheil/NormalizeQuantiles.jl) : implements quantile normalization
- [PlmDCA](https://github.com/pagnani/PlmDCA) : Pseudo Likelihood Maximization for direct-coupling analysis of protein structure from many homologous amino-acid sequences.
- [SpeedDate.jl](https://github.com/vanOosterhoutLab/SpeedDate.jl) : A utility for rapidly estimating coalescence times between sequences.
- [XSim.jl](https://github.com/reworkhow/XSim.jl) : A fast and user-friendly tool to simulate sequence data and complicated pedigree structures.

### BioJulia ecosystem

> Packages in the [BioJulia](https://biojulia.net/) organization.

- [BED.jl](https://github.com/BioJulia/BED.jl) : I/O and utilities for the BED file format.
- [BioAlignments.jl](https://github.com/BioJulia/BioAlignments.jl) :  Sequence alignment tools in BioJulia
- [BioSequences.jl](https://github.com/BioJulia/BioSequences.jl) : Biological sequences for the julia language.
- [BioStructures.jl](https://github.com/BioJulia/BioStructures.jl) : A Julia package to read, write and manipulate macromolecular structures (particularly proteins).
- [BioSymbols.jl](https://github.com/BioJulia/BioSymbols.jl) : Nucleic and amino acid primitive types.
- [BioTools.jl](https://github.com/BioJulia/BioTools.jl) : Interfaces to common external biological tools from julia scripts and programs (e.g. BLAST).
- [FASTX.jl](https://github.com/BioJulia/FASTX.jl) : Parse and process FASTA and FASTQ formatted files of biological sequences.
- [GeneticVariation.jl](https://github.com/BioJulia/GeneticVariation.jl) : types and methods for working with genetic variation.
- [GenomeGraphs.jl](https://github.com/BioJulia/GenomeGraphs.jl) :  A modern genomics framework for julia
- [GenomicFeatures.jl](https://github.com/BioJulia/GenomicFeatures.jl) : utilities for working with interval based genomic annotations.
- [IntervalTrees.jl](https://github.com/BioJulia/IntervalTrees.jl) : A data structure for efficient manipulation of sets of intervals.
- [KmerAnalysis.jl](https://github.com/BioJulia/KmerAnalysis.jl) :  Kmer counting algorithms and count-data utilities for the BioJulia framework.
- [Microbiome.jl](https://github.com/BioJulia/Microbiome.jl) : manipulating and analyzing microbiome and microbial community data.
- [XAM.jl](https://github.com/BioJulia/XAM.jl) : Parse and process SAM and BAM formatted alignment map files.


### Phylogeny

[Wikiedia: Phylogenetics](https://en.wikipedia.org/wiki/Phylogenetics). Phylogenic trees are evolution trees deduced from biosequences.

- [Phylogenies.jl](https://github.com/BioJulia/Phylogenies.jl) : Phylogenetic trees and geneologies. (No `Project.toml`)
- [PhyloNetworks.jl](https://github.com/crsl4/PhyloNetworks.jl) : A Julia package for statistical inference, data manipulation and visualization of phylogenetic networks. The companion package for plotting is [PhyloPlots.jl](https://github.com/cecileane/PhyloPlots.jl)
- [PhyloTrees.jl](https://github.com/jangevaare/PhyloTrees.jl) : Phylogenetic tree simulation.

### Genomics

**Resources**

- [Wikipedia: GWAS](https://en.wikipedia.org/wiki/Genome-wide_association_study)
- [Wikipedia: list of RNA-Seq bioinformatics tools](https://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools), not many of which are in Julia but depending on the language, they may have an API.
- [Data Analysis for Genomics](https://genomicsclass.github.io/book/) : with R programming language but FYI.

**Packages**

- [JWAS.jl](https://github.com/reworkhow/JWAS.jl) : An open-source software tool for Bayesian multiple regression methods applied to genome-wide association studies (GWAS) and genomic prediction.
- [MendelBase.jl](https://github.com/OpenMendel/MendelBase.jl) : contains the base functions of OpenMendel.
- [PopGen.jl](https://github.com/BioJulia/PopGen.jl) : Population Genetics in Julia.
- [SnpArrays.jl](https://github.com/OpenMendel/SnpArrays.jl) : provides utilities for handling compressed storage of biallelic SNP (Single-Nucleotide Polymorphism) data.


## Metabolic networks

- [COBRA.jl](https://github.com/opencobra/COBRA.jl) : COnstraint-Based Reconstruction and Analysis, used to perform COBRA analyses such as Flux Balance Anlysis (FBA), Flux Variability Anlysis (FVA), or any of its associated variants such as `distributedFBA`.
- [COBREXA.jl](https://github.com/LCSB-BioCore/COBREXA.jl) : constraint-based reconstruction and analysis tools for exa-scale metabolic models in Julia. It uses [JuMP.jl](https://github.com/jump-dev/JuMP.jl) to formulate optimization problems.
- [Escher.jl](https://github.com/stelmo/Escher.jl) : `escherplot` is a `Makie.jl` recipe that plots maps of metabolic models.

## Molecular Biology

- [CellFishing.jl](https://github.com/bicycle1885/CellFishing.jl) : (cell finder via hashing) is a tool to find similar cells of query cells based on their transcriptome expression profiles, a.k.a. single-cell sequencing.


## Microscopy and bioimages

[Wikipedia: Microscopy](https://en.wikipedia.org/wiki/Microscopy)

- [BioformatsLoader.jl](https://github.com/ahnlabb/BioformatsLoader.jl) : load images using bioformats based on `JavaCall.jl`.
- [DeconvOptim.jl](https://github.com/roflmaostc/DeconvOptim.jl) : A multi-dimensional, high performance deconvolution framework written in Julia Lang for CPUs and GPUs. [JuliaCon 2021 video](https://youtu.be/FodpnOhccis)
- [FourierTools.jl](https://github.com/bionanoimaging/FourierTools.jl) : Tools for working with Fourier (Frequency ) space. [JuliaCon 2021 video](https://youtu.be/qYgJDb_Ko2E)
- [ImagineFormat.jl](https://github.com/timholy/ImagineFormat.jl) : Read [.imagine](http://dotwhat.net/file/extension/imagine/7604) light sheet microscopy file formats in Julia.
- [MicroscopyLabels.jl](https://github.com/tlnagy/MicroscopyLabels.jl) : Embed annotations in your microscopy images.
- [PSFs.jl](https://github.com/RainerHeintzmann/PSFs.jl) : Toolbox for calculating optical [PSFs](https://en.wikipedia.org/wiki/Point_spread_function).
- [View5D.jl](https://github.com/RainerHeintzmann/View5D.jl) : a Java-based viewer for up to 5-dimensional data.
- 🏚️ [EMIRT.jl](https://github.com/seung-lab/EMIRT.jl) : Electron Microscopy Image Reconstruction Toolbox using julia language. (No `Project.toml`)

## Neuroscience

[CodeNeuro](http://codeneuro.org/) : Bringing neuroscience and data science together.

- [BrainWave.jl](https://github.com/sam81/BrainWave.jl) : Julia functions to process electroencephalographic (EEG) recordings.
- [DCEMRI.jl](https://github.com/davidssmith/DCEMRI.jl) : A Fast, Validated Toolkit for Dynamic Contrast Enhanced MRI Analysis. A paper on the code is in press at [PeerJ](https://peerj.com/preprints/670/).
- [NeuroAnalysis.jl](https://github.com/babaq/NeuroAnalysis.jl) : Julia package for neural signal analysis.
- [Neuroimaging.jl](https://github.com/rob-luke/Neuroimaging.jl) : Process neuroimaging data using the Julia language.
- [NeuronBuilder](https://github.com/Dhruva2/NeuronBuilder) : Builds conductance based neural networks iteratively, from ion channels and synapses.
- [OpenEphysLoader.jl](https://github.com/galenlynch/OpenEphysLoader.jl) : A set of tools to load data written by the Open Ephys GUI.

## Healthcare

[Wikipedia: Biomedicine](https://en.wikipedia.org/wiki/Category:Biomedicine)

- [DICOM.jl](https://github.com/JuliaHealth/DICOM.jl) : Julia package for reading and writing DICOM (Digital Imaging and Communications in Medicine) files. [DICOMClient.jl](https://github.com/JuliaHealth/DICOMClient.jl)  provides a Julia client for connecting to servers.
- [ICD_GEMs.jl](https://github.com/InPhyT/ICD_GEMs.jl): translate ICD-9 codes in ICD-10 and viceversa via the General Equivalence Mappings (GEMs). ICD stands for International Classification of Diseases.
- [openBF](https://github.com/INSIGNEO/openBF) : A finite-volume solver for 1D elastic arterial blood flow networks.
- [PharmaceuticalClassification.jl](https://github.com/JuliaHealth/PharmaceuticalClassification.jl) : Mappings between different systems for classifying medications.

## Pharmacology

[Wikipedia: Pharmacology](https://en.wikipedia.org/wiki/Pharmacology)

See also [Pumas AI](https://github.com/PumasAI), the commercial framework for Pharmaceutical Modeling and Simulation in Julia.

- [DataInterpolations.jl](https://github.com/PumasAI/DataInterpolations.jl) : A library of data interpolation and smoothing functions.
- [PumasTutorials.jl](https://github.com/PumasAI/PumasTutorials.jl) : Tutorials for pharmaceutical modeling and simulation with Pumas.jl. https://tutorials.pumas.ai
