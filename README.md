# Mitigation Spatial

**Inyo County Water Department**  
*Inventory mitigation project spatial boundaries - make available to interested parties*

## Overview

This repository contains spatial data about mitigation sites.

- **Source**: `data/gis/Mitigation_PointsAGOL.csv`
- **Geometry**: Point locations (lat/lon coordinates)
- **Updates**: Real-time updates from Google Sheets on project status

- **Source**: `data/gis/mit_points/mitigation_sites.shp`
- **Geometry**: Polygon boundaries
- **Format**: ESRI Shapefile

## Repository Structure

```
├── index.qmd              # Main Quarto document with maps and analysis
├── data/                  # Spatial data files
│   └── gis/              # GIS data (CSV, shapefiles)
├── docs/                 # Rendered website files
├── output/               # Analysis outputs and exports
├── www/                  # Website assets (logos)
├── styles.css            # Custom CSS styling
└── README.md             # This file
```

## Data Downloads

Spatial data files are available for download:
- **CSV Points GeoJSON**: GeoJSON format of point locations
- **CSV Points Shapefile**: ESRI Shapefile format of points
- **Mitigation Polygons GeoJSON**: GeoJSON format of polygon boundaries
- **Mitigation Polygons Shapefile**: ESRI Shapefile format of polygons

## Reproducing the Analysis

### Prerequisites
- R (≥ 4.0)
- RStudio (recommended)
- Git

### Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/zach-nelson/mitigation-spatial.git
   cd mitigation-spatial
   ```

2. **Install Required R Packages**:
   ```r
   install.packages(c("tidyverse", "sf", "DT", "ggplot2", "ggrepel", "RColorBrewer", "quarto"))
   ```

3. **Render the Website**:
   ```bash
   quarto render
   ```

### Key R Packages
- `tidyverse` - Data manipulation
- `sf` - Spatial data processing
- `DT` - Interactive tables
- `ggplot2` - Static maps
- `ggrepel` - Label placement
- `RColorBrewer` - Color palettes
- `quarto` - Dynamic document generation

## Contributing

1. **Fork the Repository** on GitHub
2. **Create a Feature Branch**: `git checkout -b feature-name`
3. **Make Changes** and test locally
4. **Commit Changes**: `git commit -m "Descriptive message"`
5. **Push to Fork**: `git push origin feature-name`
6. **Open a Pull Request** with detailed description

## Contact & Support

- **Repository**: [github.com/zach-nelson/mitigation-spatial](https://github.com/zach-nelson/mitigation-spatial)
- **Live Website**: [zach-nelson.github.io/mitigation-spatial](https://zach-nelson.github.io/mitigation-spatial)
- **Issues**: [Report bugs or request features](https://github.com/zach-nelson/mitigation-spatial/issues)

## License

MIT License

Copyright (c) 2025 Zach Nelson

---

*Last updated: November 2025*

