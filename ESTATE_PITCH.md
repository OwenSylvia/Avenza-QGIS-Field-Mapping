# Refugio Pass Estate Management & Hospitality Geospatial Framework
**Comprehensive Field Audit Portfolio | 16.2-Mile Operations & Guest Experience Proof-of-Concept**

## Executive Summary
This independent project serves as a premium commercial proof-of-concept for high-end private estates, multi-acre ranches, and luxury wineries looking to optimize their spatial asset management and elevate their guest experiences. Utilizing a 16.2-mile backcountry footprint along Refugio Pass (Santa Ynez Mountains), this project demonstrates an end-to-end framework for mobile data acquisition, interactive asset tracking, and ecological resource mapping.

Large geographic properties face distinct challenges balancing operational logistics, fire mitigation, and guest satisfaction.. This repository demonstrates how raw field data is converted into high-precision, software-ready deliverables (GeoJSON layers) that assist operations and improve the visitor experience:

1. **Guest Experience & Terroir Storytelling:** Creating visual resources that enable estates to create immersive, carefully planned excursions, such as mapping native habitat boundaries, environmental zoning, and customized experience itineraries that allow visitors to uncover the core character of the land.
2. **Operations & Risk Management:** Giving estate managers interactive, geotagged danger coordinates to effectively deploy maintenance teams and reduce property liability, ensuring a smooth and secure behind-the-scenes experience.
   
## Commercial Value Metrics (KPIs)
* **Total Audited Footprint:** 16.2 Miles of Continuous Spatial Field Tracking
* **Resource Assessment Locales:** Discrete point features logging botanical zones and pathway infrastructure.
* **Data Standards:** Non-Proprietary Open-Source Web-Optimized GeoJSON.

## Spatial Visualization
Below is the finalized premium estate layout displaying the 16.2-mile trail network corridor, categorized ecological assets, and structural preservation priorities overlaid on high-resolution global satellite imagery.

![Refugio Pass Estate Map Layout](Final_Map_Output.png)

**Interactive Map**: With descriptions and photos.
<iframe src="https://owensylvia.github.io/Avenza-QGIS-Field-Mapping/" width="100%" height="500" style="border:none;"></iframe>


## Operational Methodology & Field Implementation
1. **Mobile Data Capture:** Spatial tracking paths and asset vectors were mapped dynamically on-the-ground using advanced mobile GPS data collectors while navigating the terrain.
2. **System Integration:** Raw spatial vector information was exported as a unified data packet and integrated into a professional desktop GIS suite (**QGIS 3.44 LTR**) for data isolation, validation, and styling.
3. **Web Optimization:** Coordinates were scrubbed and packaged into lightweight GeoJSON structures to ensure the maps can load seamlessly on standard mobile browsers, estate tablets, or via tasting room QR codes.
4. **Cartographic Georeferencing:** Property vectors were perfectly aligned and georeferenced over projected high-resolution satellite imagery, verifying real-world accuracy down to individual canopy and pathway boundaries.

## Property Attribute & Classification Schema

### Estate Hospitality & Ecological Zoning
Mapping native plant boundaries allows estates and wineries to create educational guest trail networks, build self-guided vineyard tours, and monitor ecological assets:
* **Chaparral Slopes:** Identifying dense native woody shrublands (Chamise, Manzanita, Ceanothus) along property margins to analyze microclimates and prioritize mandatory seasonal wildfire fuel-load abatement.
* **Oak Woodland:** Mapping protected native canopy resources (such as mature Coast Live Oaks). This allows hospitality teams to map shaded guest recreational trails, picnic overlooks, or identify critical wildlife habitat zones.
* **Grassland clearings:** Cataloging open, sun-exposed meadows to evaluate soil exposure margins for potential future vineyard block expansion, lavender fields, or olive grove placement.

### Infrastructure Logistics & Liability Mitigation
To maintain secure access routes for estate operations, emergency vehicles, and guest safety, pathway infrastructure features were surveyed and classified by preservation urgency:

* **Geological Slope & Erosion Concerns:** 
  * *Minor:* Light, stable soil movement safely off the main vehicle or hiking path.
  * *Moderate:* Active rock fragmentation presenting a minor clearing priority to maintain smooth road access.
  * *Severe:* Unstable rock formations or deep washouts requiring immediate crew routing to eliminate property degradation and guest liability.
* **Downed Trees & Boundary Blockages:**
  * *Minor:* Small fallen branches easily cleared beside the trail network margin.
  * *Moderate:* Medium timber fall slightly narrowing the pathway or impacting perimeter fencing.
  * *Severe:* Large timber completely blocking access roads, requiring immediate chainsaw deployment to restore emergency vehicle clearance.
* **Overgrowth & Encroachment Monitoring:** Continuous monitoring field column to identify where aggressive flora encroaches on guest clearance boundaries. 

## Digital Asset Deliverables Folder
* `Refugio_Tracking_Line.geojson` - Main infrastructure vector path detailing 16.2 miles of exact continuous trail/road placement, track data, and 3D elevation slope values.
* `vegetation.type.geojson` - Categorized botanical point file mapping estate habitat zones, vineyard expansions, and fuel clearance zones.
* `trail.conditions.geojson` - Structural risk ledger tracking specific operational hazards and maintenance locations.
* `Final_Map_output.png` - High-resolution printable presentation document designed for tasting room displays or executive operational briefs.
* `.gitignore` - System configuration file ensuring messy temporary local software data remains hidden from the clean public repository.
