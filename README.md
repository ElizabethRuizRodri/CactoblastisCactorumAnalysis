# CactoblastisCactorumAnalysis

Analysis in *Cactoblastis cactorum* of the native region (Argentina) with ddRAD data. 

Process:
* We added the basic analysis command lines (structure and diversity)-> See Structure and diversity basic analysis script.txt file.
* We tested if there is an association between genetic structure and geography with a Mantel test. -> See Mantel test.txt file.
* We make a RDA to find candidate SNPs possibly associated to environmental variables -> See Redundancy Analysis (RDA) script.txt file.
* We make a LFMM test to find candidate SNPs associated to environment variables and support the RDA analysis.

NOTE: The important variables to *Cactoblastis cactorum* establishment are: Annual Mean Temperature, 
Annual Precipitation, Temperature Annual Range, Precipitation Seasionality and soil pH of first five centimetres (N. Castillo, personal communication, March 7, 2022).

Data was previously filtered with vcftools and plink1.9:
* min_alleles and max alleles=2 
* missing data=0.8
* MAF=0.05
* HWE=0.05
* LD(linkage disequilibrium)=0.25

We obtained 7,552 SNPs with 224 individuals.

* Environmental variables values were obtained with WorldClim (worldclim.org/data/bioclim.html) and SoilGrids (soildgrids.org).
