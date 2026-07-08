# Changelog

All notable changes to this project will be documented in this file.

## [1.2] - 2026-07-07

### Added

- Added a hyperparameter tuning helper to assist in pick values before running the main figure.
- Added an interactive "Map width" slider to the network + map figure, letting users trade space between the network plot and the geospatial map.
- Generalized categorical variable coloring (e.g. cluster labels) to support non-continuous attributes to color networks by.

### Changed

- Reworked the network + map figure layout to be more customizable.

### Fixed

- Removed unused imports (`pyvis`, `networkx.algorithms.bipartite`, `scipy`, scikit-learn's `PCA`/`KMeans`/`silhouette_score`, `os`, `imageio`, `matplotlib.colors`) that were never referenced in the notebook.

## [1.1.1] - 2026-03-24

### Changed

- Edited functions to be able to label sample nodes if desired.

## [1.1] - 2026-03-17

### Added

- Turned script into more modular functions, increasing ease of use. Now users only need to edit the hyperparameter cell and the main execution cell.

## [1.0] - 2025-06-07

### Added

- Original version of GeoChemNet, published and utilized to create article "GeoChemNet: An interactive tool for visualizing and interpreting outliers in geochemical data using networks", https://doi.org/10.1016/j.apgeochem.2026.106712.
