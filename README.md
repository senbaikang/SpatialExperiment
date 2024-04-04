# SpatialExperiment

[![R build status](https://github.com/drighelli/SpatialExperiment/workflows/R-CMD-check-bioc/badge.svg)](https://github.com/drighelli/SpatialExperiment/actions)

`SpatialExperiment` is an R/Bioconductor S4 class for storing data from spatial -omics experiments. The class extends the `SingleCellExperiment` class for single-cell data to support storage and retrieval of additional information from spot-based and molecule-based platforms, including spatial coordinates, images, and image metadata. A specialized constructor function is included for data from the 10x Genomics Visium platform.

The `SpatialExperiment` package is available from [Bioconductor](https://bioconductor.org/packages/SpatialExperiment).

A vignette containing examples and documentation is available from [Bioconductor](https://bioconductor.org/packages/SpatialExperiment), and additional details are provided in our [paper](https://doi.org/10.1093/bioinformatics/btac299).

The following schematic illustrates the `SpatialExperiment` class structure.

<img src="vignettes/SPE.png" width="800"/>


## Installation

The current release version of the `SpatialExperiment` package can be installed from Bioconductor as follows. This is the recommended approach for most users.

```
install.packages("BiocManager")
BiocManager::install("SpatialExperiment")
```

The latest development version can be installed from the [development version of Bioconductor](https://contributions.bioconductor.org/use-devel.html) or from GitHub (which may also require some dependency packages to be installed manually).

```
remotes::install_github("drighelli/SpatialExperiment")
```


## Citation

Righell D.\*, Weber L.M.\*, Crowell H.L.\*, Pardo B., Collado-Torres L., Ghazanfar S., Lun A.T.L., Hicks S.C.<sup>+</sup>, and Risso D.<sup>+</sup> (2022). *SpatialExperiment: infrastructure for spatially-resolved transcriptomics data in R using Bioconductor.* [Bioinformatics](https://doi.org/10.1093/bioinformatics/btac299), 38(11), 3128-3131.
