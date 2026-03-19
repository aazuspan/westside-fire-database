# A Spatial Database of Historical Westside Fire

[![DOI](https://zenodo.org/badge/1186680613.svg)](https://doi.org/10.5281/zenodo.19120166)

This repository contains datasets for "A spatial database of historical fire in westside forests of the Pacific Northwest" (in press) by Zuspan et. al., 2026 in [GeoPackage](/gpkg) and [Shapefile](/shp) formats.

See the publication (available soon) for details.

## Metadata fields

| Description                                                                 | .gpkg Field Name         | .shp Field Name*    |
|-----------------------------------------------------------------------------|--------------------------|---------------------|
| Unique identifier for the record                                            | uuid                     | uuid                |
| Name of the fire event, where available                                     | name                     | name                |
| Year of the fire event (or year of survey for forest condition maps)        | year                     | year                |
| Calculated area of the fire perimeter in hectares                           | hectares                 | hectares            |
| Data source name and year                                                   | source_author            | source              |
| Data collection methodology category                                        | source_type              | type                |
| Spatial coverage / study area of the data source                            | source_extent            | extent              |
| Assigned confidence in spatial accuracy                                     | spatial_confidence       | spat_conf           |
| Assigned confidence in temporal accuracy                                    | temporal_confidence      | temp_conf           |
| Additional notes compiled from other fields                                 | comments                 | comments            |

*Names vary slightly between the GeoPackage and Shapefile formats due to Shapefile length constraints.