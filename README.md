### Xenium and matching samples snRNA-seq data pre-processing and analysis for the manuscript: "High-resolution spatial profiling reveals localised immune responses after cardiac base editing"
#### 1. Xenium
Raw Xenium data were processed with Xenium Ranger. Cell segmentation was subsequently refined using the resegment pipeline with the segment-large-cells option to account for the large size of cardiomyocytes.

#### 2. snRNA-seq
snRNA-seq data was generated from the Xenium matched bottom heart halves. The raw data was processed with Cell Ranger.

#### Analysis was run with Python  3.11.14 and the following dependancies:
anndata              0.12.6
dask                 2024.11.2
datashader           0.18.2
geopandas            1.1.1
h5py                 3.14.0
igraph               1.0.0
leidenalg            0.11.0
matplotlib           3.10.7
networkx             3.5
numba                0.62.1
numpy                2.3.4
omnipath             1.0.12
pandas               2.3.3
pyarrow              21.0.0
pynndescent          0.5.13
scanpy               1.11.2
scikit-learn         1.7.2
scikit-misc          0.5.1
scipy                1.16.3
seaborn              0.13.2
shapely              2.1.2
spatialdata          0.4.0
spatialdata-io       0.5.1
spatialdata-plot     0.2.13
squidpy              1.6.5
statsmodels          0.14.5
tifffile             2025.10.16
umap-learn           0.5.9.post2
xarray               2024.11.0
zarr                 2.18.7
