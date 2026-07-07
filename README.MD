# Population Exposure Modeling

A Python notebook for generating **building-level daytime and nighttime population distributions** by combining WorldPop population data, building footprints, OpenStreetMap building types, and household-size statistics.

## Features

- Allocate WorldPop population to residential buildings
- Simulate household composition
- Generate synthetic nighttime and daytime populations
- Produce building- and individual-level exposure datasets
- Visualize population distributions

## Requirements

- Python 3.10+
- geopandas
- rasterio
- pandas
- numpy
- shapely
- matplotlib

Install dependencies with:

```bash
pip install geopandas rasterio pandas numpy shapely matplotlib
```

## Inputs

- WorldPop population raster
- Building footprint shapefile
- OpenStreetMap building data
- CORESIDENCE household-size dataset

## Outputs

- Building population estimates
- Synthetic individual population (day/night)
- Population maps

## Applications

- Flood and earthquake exposure
- Risk assessment
- Evacuation planning
- Urban resilience studies

## License

Specify your preferred license (e.g., MIT).
