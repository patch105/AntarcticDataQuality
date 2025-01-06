# AntarcticDataQuality

<a href="https://zenodo.org/badge/latestdoi/641286171"><img src="https://zenodo.org/badge/641286171.svg" alt="DOI"></a>

The primary aim of this project is to assess the data quality of the most comprehensive set of biological records ever available for terrestrial Antarctica, the Biodiversity of Ice-Free Antarctica Database. The database offers unprecedented opportunities for modelling biodiversity across the continent, however models must be built with regard to existing limitations.

The project aims, methods, results, and discussion are presented in our paper entitled: "A multidimensional assessment of Antarctic terrestrial biological data". Patterson C.R., K.J. Helmstedt, A. Terauds and J.D. Shaw.

Please see Terauds et al. ('The Biodiversity of Ice-Free Antarctica Database') for a description of the database and its construction.

The code presented here includes:
- Terrestrial_Antarctic_Biodiversity_Database_Cleaning.html: R Markdown document of database cleaning prior to analysis.
- Geographic_Coverage.html : R Markdown document of geographic coverage analysis.
- Geographic_Bias.html : R Markdown document of geographic bias analysis.
- Temporal_Coverage.html : R Markdown document of temporal coverage analysis.
- Taxonomic_Coverage.html : R Markdown document of taxonomic coverage analysis.
- Environmental_Coverage.html : R Markdown document of environmental coverage analysis.
- Additional_functions.zip : A zip file containing R code for additional required functions.

The data used in analyses (not provided here) includes:
- The SCAR Antarctic Digital Database (ADD) rock outcrop layer (v. 7.3).
- The Antarctic Conservation Biogeographic Regions, downloaded from the Australian Antarctic Data Centre.
- The SCAR Antarctic Digital Database (ADD) high resolution coastline polygon (v. 7.5).
- The COMNAP register of Antarctic Facilities, downloaded from https://github.com/PolarGeospatialCenter/comnap-antarctic-facilities/releases/tag/v3.3.0.
- The ten environmental layers used in an assessment of Environmental Coverage. See Methods, Environmental Coverage (Main Text) and Appendix S2, Figure S1 and Table S1 for layer descriptions. Layers available on request.

Additional data provided here:
- PTM_rankings.csv : The classification of priority threat management functional groups in terms of group 'intactness' and the presence or absence of a 'wallacean' shortfall. Explanation in Methods, Taxonomic Coverage (Main Text).

Raster outputs of geographic, temporal, and environmental coverage are saved as tiffs:
- Output_coverage_tiffs.zip

Contact Charlotte Patterson at crpattrsn@gmail.com for queries.
