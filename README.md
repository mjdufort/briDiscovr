# briDiscovr

Functions implementing and supporting the "Distribution analysis across clusters of a parent population overlaid with a rare subpopulation" (DISCOV-R) analysis method (Wiedeman, Muir, et al. 2020).

## Dependencies

This package depends on bioconductor packages, which may run into issues when installing automatically. If you encounter any difficulties during installation, you can manually install the bioconductor dependencies using the following code:

```R
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
    
BiocManager::install("flowCore")
BiocManager::install("ComplexHeatmap")
BiocManager::install("Rtsne")
BiocManager::install("umap")
```
