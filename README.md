# Refugio Pass Field Survey & Environmental Mapping Project

## Project Overview
This is an independent GIS field project focused on mapping trail infrastructure, evaluating backcountry geographical conditions, and cataloging local flora groups of Refugio Pass. Using mobile data acquisition tools and desktop spatial analysis, this project produces a baseline geographic record of the ecological distribution and pathway degradation in the Santa Ynez mountain range.

## Spatial Visualization
The completed map layout is shown below, with high-resolution global satellite imagery projected on the field survey track, classified vegetation communities, and highlighted trail preservation issues.

![Refugio Pass Field Map](Final_Map_output.png)

## Data Collection & Methodology
**Field Data Acquisition:** Avenza Maps were used to actively gather geographic tracks, geospatial positions, and localized field notes while navigating the Refugio Pass.
**Data Integration:** Raw spatial tracking data was successfully integrated into **QGIS 3.44 LTR** for data isolation and cleanup after being exported as a compressed vector package (`.kmz`).
**Desktop Processing:** To neatly maintain attribute tables and geometric properties, geospatial coordinates and temporary file structures were separated and transformed into web-optimized **GeoJSON** layers.
**Basemap Alignment:** Using the **QuickMapServices** plugin to query and project **Google Satellite** images, spatial data layers were georeferenced and validated.

## Field Attribute & Classification Schema

### Vegetation Community Layers
Three main botanical classes that are representative of the local chaparral-woodland transition were identified by cataloging and mapping the plant zones along the pass:
* **Chaparral:** The steep, exposed mountain sides are home to dense, drought-tolerant woody shrublands, including chamise, manzanita, and ceanothus.
* **Grassland:** open grassy zones and clearings that are often found along ridgelines and damaged route margins. These areas are dominated by seasonal grasses.
**Oak Woodland:** Mature native oak tree stands, like Coast Live Oak, dominate canopy zones, offering vital habitat coverage and shade in moisture-retaining recesses and canyon bottoms.

### Trail Conditions Layer
During tracking navigation, infrastructure data points were assessed and categorized according to the urgency of structural preservation:
* **Erosion**: (Minor, Moderate, Severe): **Minor:** light, mostly stable erosion off clear pathway. **Moderate:** Larger, more unstable rock erosion in danger of falling into pathway. **Severe:** Heavy and unstable erosion of rock formations likely to fall and cause damage. 
**Downed Trees**: (Minor, Moderate, Severe): **Minor:** Small tree or branches fallen into or beside trail. **Moderate:** medium sized trees or branches fallen off the path or trees conflicting with the trail. **Severe:** large trees fallen into and blocking pathway.
**Overgrowth**: (Minor, Moderate, Severe): Flora or any type of greenery conflicting with trail, no cases were observed or cataloged. 

## Repository Contents
* project_tracking_line.geojson` - Web-optimized track vector file containing continuous GPS navigation paths, elevations, and track data up the pass.
* `vegetation_type_geojson` - Categorized point vectors indicating specific vegetation classes.
* `trail_conditions_geojson` - Point vectors marking infrastructure and trail accessibility hazards.
* `Final_Map_output.png` - Finalized high-resolution printable cartographic layout document.
* `.gitignore` - Repository system configuration to prevent local QGIS runtime metadata or lock files from publishing.
