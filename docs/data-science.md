# Data Science

> Data retrieval, manipulation, and storage in Julia.

**Organizations**

- [Julia ML](https://github.com/JuliaML)
- [Julia Data](https://github.com/JuliaData)
- [Julia Databases](https://github.com/JuliaDatabases)
- [Julia stats](https://github.com/JuliaStats)

## Data Manipulation

- [Cleaner.jl](https://github.com/TheRoniOne/Cleaner.jl) : A toolbox of simple solutions for common data cleaning problems.
- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) : In-memory tabular data in Julia.
- [DataFramesMeta.jl](https://github.com/JuliaStats/DataFramesMeta.jl) : Metaprogramming tools for `DataFrame`s and `AbstractDict` objects. These macros improve performance and provide more convenient syntax.
- [DFMacros.jl](https://github.com/jkrumbiegel/DFMacros.jl) : an opinionated take on DataFrame manipulation in Julia with a syntax geared towards clarity, brevity and convenience.
- [IndexedTables.jl](https://github.com/JuliaData/IndexedTables.jl) : Tabular data structures where some of the columns form a sorted index.
- [InMemoryDatasets.jl](https://github.com/sl-solution/InMemoryDatasets.jl) : Multithreaded package for working with tabular data in Julia.
- [Pandas.jl](https://github.com/JuliaPy/Pandas.jl) : A Julia front-end to Python's `pandas` package.

## DataBase API

- [DBInterface.jl](https://github.com/JuliaDatabases/DBInterface.jl) : An abstract DBI interface to provide a database-independent API protocol that all database drivers can be expected to comply with.
- [JDBC.jl](https://github.com/JuliaDatabases/JDBC.jl) : Julia interface to Java database drivers.
- [LevelDB.jl](https://github.com/jerryzhenleicai/LevelDB.jl) : Julia interface to Google's LevelDB key value database.
- [Memcache.jl](https://github.com/tanmaykm/Memcache.jl) : Julia memcached client.
- [ODBC.jl](https://github.com/quinnj/ODBC.jl) : A low-level ODBC interface for the Julia programming language. [Tabular Data I/O in Julia](https://randyzwitch.com/julia-import-data/)

## HDF5 format

[HDF5](https://www.hdfgroup.org/solutions/hdf5/) format

- [HDF5.jl](https://github.com/JuliaIO/HDF5.jl) : Save and load data in the HDF5 file format from Julia.
- [JLD2.jl](https://github.com/JuliaIO/JLD2.jl) : HDF5-compatible file format in pure Julia.

## Relational Database Management Systems and SQL

- [LibPQ.jl](https://github.com/invenia/LibPQ.jl) : A Julia wrapper for the PostgreSQL libpq C library.
- [MySQL.jl](https://github.com/JuliaDatabases/MySQL.jl) : Julia bindings and helper functions for MariaDB/MySQL C library.
- [Octo.jl](https://github.com/wookay/Octo.jl) : an SQL Query DSL in Julia.
- [SparkSQL.jl](https://github.com/propelledanalytics/SparkSQL.jl) : working with Apache Spark data using just SQL.
- [SQLite.jl](https://github.com/JuliaDatabases/SQLite.jl) : Julia interface to the SQLite library with support for operations on DataFrames.
- [SQLStrings.jl](https://github.com/JuliaComputing/SQLStrings.jl) : It provides the @sql_cmd macro to allow SQL query strings to be constructed by normal-looking string interpolation but without risking SQL formatting errors or SQL injection attacks on your application.

## NOSQL databases

- [CQLdriver.jl](https://github.com/r3tex/CQLdriver.jl) : Interfacing with CQL compliant databases. Used with `DataFrames.jl`.
- [DataKnots.jl](https://github.com/MechanicalRabbit/DataKnots.jl) : An extensible, practical and coherent algebra of query combinators.
- [LMDB.jl](https://github.com/wildart/LMDB.jl) : A wrapper interface to [Lightning Memory-Mapped Database](https://en.wikipedia.org/wiki/Lightning_Memory-Mapped_Database) (LMDB) key-value embedded data store.
- [Mongo.jl](https://github.com/ScottPJones/Mongo.jl) : Mongo bindings for the Julia programming language.
- [Mongoc.jl](https://github.com/felipenoris/Mongoc.jl) : MongoDB bindings (newer) and a wrapper around libbson, for the Julia language.
- [Redis.jl](https://github.com/JuliaDatabases/Redis.jl) : A fully-featured Redis client for the Julia programming language.

## Accessing datasets

- [DataDeps.jl](https://github.com/oxinabox/DataDeps.jl): reproducible data setup for reproducible science.
- [FaceDatasets.jl](https://github.com/dfdx/FaceDatasets.jl) : A package for easy access to face-related datasets.
- [Faker.jl](https://github.com/neomatrixcode/Faker.jl) : A package that generates fake data.
- [MLDatasets](https://github.com/JuliaML/MLDatasets.jl) : Utility package for accessing common Machine Learning datasets in Julia
- [PubMedMiner.jl](https://github.com/JuliaHealth/PubMedMiner.jl) : Return and analyze a PubMed/Medline search using MESH descriptors and their corresponding UMLS concept.
- [RDatasets.jl](https://github.com/JuliaStats/RDatasets.jl) : Julia package for loading many of the datasets available in R.
- [WorldBankData.jl](https://github.com/4gh/WorldBankData.jl) : The [World Bank](https://data.worldbank.org/) data.

## Resource

- Blog on [The Lesser Known Normal Forms of Database Design](http://www.johnmyleswhite.com/notebook/2014/09/10/the-lesser-known-normal-forms/)
- [Database-like ops benchmark](https://h2oai.github.io/db-benchmark/) of different languages and libraries.
- [Julia-data-science](https://github.com/tirthajyoti/Julia-data-science) : Notebooks on DS basics with Julia and why it is suitable for data science.
- [Julia DataFrames Tutorial](https://github.com/bkamins/Julia-DataFrames-Tutorial) by Bogumił Kamiński.
