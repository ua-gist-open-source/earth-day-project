# Open Source GIS Earth Day Project
## Assignment
In this assignment you will use what you have learned over the semester to highlight some ongoing or recent changes to the earth's surface.

## Background
The earth is changing every day. With a wide variety of satellite and aerial-borne sensors, we have the ability to monitor these changes in
almost real-time. In this lab we will use publicly available satellite imagery to show rapid changes to the earth's surface. I will
demonstrate using Landsat data but you are welcome to use other imagery so long as it comes from a publicly available source.

The final product will be a cartographic product highlighting how your area of interest has changed. What you choose to focus on is up 
to you. Some ideas:
- volcanic eruptions
- deforestation
- urban sprawl
- forest fire
- flooding
- landslides
- open pit mine
- glaciers calving/melting
- concentrated animal feed operations

If you don't know where/when to find something, look at recent news for ideas.

Background reading:
- Sentinel 2
  - [Sentinel](https://sentinels.copernicus.eu/web/sentinel/home)
  - [Landsat](https://landsat.gsfc.nasa.gov/)
- Sources
  - [Earth Explorer](https://earthexplorer.usgs.gov/)
  - [EO Browser](https://apps.sentinel-hub.com/eo-browser/)
- Band-derived indexes
  - [Sentinel 2](https://custom-scripts.sentinel-hub.com/custom-scripts/sentinel-2/indexdb/)
  - [Landsat](https://www.usgs.gov/landsat-missions/landsat-surface-reflectance-derived-spectral-indices)

## Objective
Demonstrate change. Change is dynamic. There are different ways of highlighting change, including but not limited to:
- Time series comparisons
- Change analysis
  - Change detection, image differencing, scatter plots, classification matrices
- Indexes
  - Different band combinations, ratios, or normalized differences can really highlight a physical attribute on the landscape.
- Graphs
  - Indexes over time, aggregated by region (like the rasterio NDVI time series)

## Notes
This assignment is a lot more flexible than previous assignments. Please use QGIS for your final cartographic product. For processing 
you are welcome to use a codespace. 

## Creativity
This class has lacked in opportunities to be creative so let's unleash that potential. Be creative in what you choose and how you 
present it.

## Deliverables
Submit a pull request to merge your `assignment` branch with `master` (but do not merge). The `assginment` branch should include:
- `earth-day-map.pdf` - cartographic product produced in QGIS that tells a story of recent earth changes
  - Two maps (before/after)
  - Should use an index (e.g., NDVI, NBR, PCA, etc)
- `methods.md` - a text markdown file describing your methods, including:
  - data sources
  - software used
  - license restrictions associated with data use
  - This _should_ be reflected in either the map or the notebook but more details can be provided in the `methods.md` file. 
