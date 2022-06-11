# Earth Science

Climate modeling, ecology, cartography, GIS, Meteorology, etc., in Julia.

**Organizations**

- [Julia space](https://github.com/JuliaSpace)
- [Julia Geo](https://github.com/JuliaGeo)
- [Julia earth](https://github.com/JuliaEarth)
- [EcoJulia](https://ecojulia.org)
- [Julia climate](https://github.com/JuliaClimate)
- [Julia ocean](https://github.com/JuliaOcean)

## Seismology

[Wikipedia: Seismology](https://en.wikipedia.org/wiki/Seismology)

- [JUDI.jl](https://github.com/slimgroup/JUDI.jl): a framework for large-scale seismic modeling and inversion.

## Space

- [ReferenceFrameRotations.jl](https://github.com/JuliaSpace/ReferenceFrameRotations.jl) : Functions related to rotations of coordinate frames, angle2dcm, dcm2angle.

## Climatology

[Wikipedia: Climatology](https://en.wikipedia.org/wiki/Category:Climatology)

- [ClimateTools.jl](https://github.com/JuliaClimate/ClimateTools.jl) : This package is a collection of commonly-used tools in Climate Science.
- [INMET.jl](https://github.com/JuliaClimate/INMET.jl) : Julia API to access data from the [Instituto Nacional de Metereologia (INMET)](https://portal.inmet.gov.br/).
- [Mimi.jl](https://github.com/anthofflab/Mimi.jl) : Integrated Assessment Modeling Framework for climate change.

## Ecology

[Wikipedia: Ecology](https://en.wikipedia.org/wiki/Category:Ecology)

- [Diversity.jl](https://github.com/EcoJulia/Diversity.jl) : Diversity analysis package for Julia, with submodules containing standard ecological and other diversity measures.
- [EcologicalNetwork.jl](https://github.com/EcoJulia/EcologicalNetworks.jl) : Measure various aspects of the structure of ecological networks in Julia.
- [FishABM.jl](https://github.com/jangevaare/FishABM.jl) : An agent based life cycle model for managed fisheries. (No `Project.toml`)
- [GBIF.jl](https://github.com/EcoJulia/GBIF.jl) : Functions and types to access GBIF data from Julia.
- [SpatialEcology.jl](https://github.com/EcoJulia/SpatialEcology.jl) : Julia framework for spatial ecology - data types and utilities.

### Agronom and Forest Modelling

- [Wikipedia: Agronomy](https://en.wikipedia.org/wiki/Category:Agronomy)
- [Wikipedia: Forest Modelling](https://en.wikipedia.org/wiki/Category:Forest_modelling)

---

- [LeafAreaIndex.jl](https://github.com/ETC-UA/LeafAreaIndex.jl) : Package to calculate Leaf Area Index from Hemisperical Images. [LAIscript](https://github.com/ETC-UA/LAIscript) : scripts to automatically run Leaf Area Index (LAI) calculations with ODBC link to custom database. Needs `LeafAreaIndex.jl`.

### Aquatic Ecology

- [AIBECS.jl](https://github.com/JuliaOcean/AIBECS.jl) : Algebraic Implicit Biogeochemical Elemental Cycling System (AIBECS) for exploring global marine biogeochemical cycles.
- [OceanRobots.jl](https://github.com/gaelforget/OceanRobots.jl) : simulating data collected by autonomous, remotely operated, or manned vehicles in the Ocean. [JuliaCon 2021 video](https://youtu.be/oC-rikXfVo8)

**Resources**

[Modeling Marine Ecosystems At Multiple Scales Using Julia](https://youtu.be/UCIRrXz2ZS0), a workshop @ JuliaCon 2021.

## Cartography

[Wikipedia: Cartography](https://en.wikipedia.org/wiki/Category:Cartography)

- [Proj4.jl](https://github.com/JuliaGeo/Proj4.jl) : Julia wrapper for PROJ.4 cartographic projections library.


## Geographic information system (GIS)

[Wikipedia: GIS](https://en.wikipedia.org/wiki/Geographic_information_system)

- [GDAL.jl](https://github.com/JuliaGeo/GDAL.jl) : Thin Julia wrapper for [GDAL](https://gdal.org/) - Geospatial Data Abstraction Library. See also [ArchGDAL.jl](https://github.com/yeesian/ArchGDAL.jl) for a high level API for `GDAL.jl`.
- [Geodesy.jl](https://github.com/JuliaGeo/Geodesy.jl) : Work with points defined in various coordinate systems.
- [GeographicLibPy.jl](https://github.com/kshramt/GeographicLibPy.jl) : Thin wrapper of [geographiclib](https://pypi.python.org/pypi/geographiclib) Python package.
- [GeoInterface.jl](https://github.com/JuliaGeo/GeoInterface.jl) : A Julia Protocol for Geospatial Data.
- [GeoIP.jl](https://github.com/JuliaWeb/GeoIP.jl) : estimating the geographic location of IP addresses.
- [GeoJSON.jl](https://github.com/JuliaGeo/GeoJSON.jl) : Utilities for working with GeoJSON data in Julia.
- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) : An extensible framework for high-performance geostatistics in Julia.
- [GMT.jl](https://github.com/joa-quim/GMT.jl) :Julia wrapper for the [Generic Mapping Tools](https://github.com/GenericMappingTools/gmt)(GMT).
- [OpenStreetMap.jl](https://github.com/tedsteiner/OpenStreetMap.jl) : The Julia OpenStreetMap package provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
- [OpenStreetMapPlotter.jl](https://github.com/juliusgeo/OpenStreetMapPlotter.jl) : Plotting focused library for OpenStreetMap data.
- [OpenStreetMapX.jl](https://github.com/pszufe/OpenStreetMapX.jl) : OpenStreetMap support for Julia 1.0. The package can parse `*.osm` and `*.pbf` (contributed by @blegat) files and generate a LightGraphs representation along the metadata. [JuliaCon2021 tutorial](https://pszufe.github.io/OpenStreetMapX_Tutorial/JuliaCon2021/)
- [OpenStreetMapXPlot.jl](https://github.com/pszufe/OpenStreetMapXPlot.jl) : plotting companion for the `OpenStreetMapX.jl` package.
- [Turf.jl](https://github.com/philoez98/Turf.jl) : A geospatial engine encoding the collections of simple geographical features using the JS lib Turfjs in the GeoJSON format.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Watershed.jl](https://github.com/seung-lab/Watershed.jl) : Julia version of [watershed](https://github.com/seung-lab/watershed). (No `Porject.toml`)

</details>

## GPS

- [NMEA.jl](https://github.com/RobBlackwell/NMEA.jl) : Julia package for parsing GPS NMEA messages.
