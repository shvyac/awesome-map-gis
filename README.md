# awesome-map-gis

Useful maps / GIS tools and resources — desktop GIS, web mapping libraries, open data, cloud platforms, and Japan-focused geospatial services.

## OpenStreetMap

Crowd-sourced world map data, editing tools, and extracts. Start here for free basemap data and community tooling.

- https://www.openstreetmap.org/
- https://wiki.openstreetmap.org/
- https://overpass-turbo.eu/ — interactive Overpass API query editor
- https://www.geofabrik.de/data/download.html — regional OSM extracts
- https://nominatim.org/ — OSM-based geocoding
- https://github.com/osmlab/awesome-openstreetmap

## Desktop GIS

### QGIS
Leading free/open-source desktop GIS — editing, cartography, analysis, and a large plugin ecosystem. QGIS 4.0 (Qt6-based) was released in March 2026; the latest feature release is 4.2 (July 2026).

- https://qgis.org/
- https://docs.qgis.org/
- https://github.com/qgis/QGIS
- https://changelog.qgis.org/ — release changelogs (4.x series)

### GRASS (formerly GRASS GIS)
OSGeo raster/vector analysis suite, rebranded as “GRASS” in 2025 (current series 8.5); also available via QGIS Processing.

- https://grass.osgeo.org/
- https://github.com/OSGeo/grass

### MapWindow Open Source GIS
Windows-friendly open-source GIS desktop and related projects. The website is no longer actively updated (last copyright 2022); downloads and code are on GitHub.

- https://www.mapwindow.org/
- https://github.com/MapWindow
- https://github.com/MapWindow/MapWindow5

## ArcGIS / Esri

Commercial GIS platform (desktop, online, developer APIs) and community awesome list.

- https://developers.arcgis.com/
- https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview
- https://github.com/Esri/awesome-arcgis-developers

## Cloud & commercial map platforms

### Mapbox
Vector-tile maps, GL SDKs, geocoding, and navigation APIs.

- https://www.mapbox.com/
- https://docs.mapbox.com/

### Google Maps Platform
Maps, Places, Routes, and related developer APIs.

- https://developers.google.com/maps?hl=ja
- https://developers.google.com/maps

### Azure Maps (successor to Bing Maps for Enterprise)
Microsoft’s current maps / geospatial APIs. Bing Maps for Enterprise is deprecated — migrate to Azure Maps.

- https://learn.microsoft.com/en-us/azure/azure-maps/
- https://learn.microsoft.com/en-us/azure/azure-maps/migrate-bing-maps-overview

### MapTiler / OpenMapTiles / Stadia / Thunderforest
Hosted or self-hostable basemap tiles and styles.

- https://www.maptiler.com/
- https://openmaptiles.org/
- https://stadiamaps.com/
- https://www.thunderforest.com/

## Web mapping libraries

### Leaflet
Lightweight, widely used JS library for interactive raster-tile maps.

- https://leafletjs.com/

### MapLibre GL JS
Open-source WebGL vector-tile maps (community fork of Mapbox GL JS). Current major version is v6; supports both MVT and the new MapLibre Tile (MLT) format.

- https://maplibre.org/
- https://github.com/maplibre/maplibre-gl-js/releases — release notes

### OpenLayers
Full-featured JS mapping library — projections, WMS/WFS, editing, enterprise GIS in the browser.

- https://openlayers.org/

### CesiumJS
3D globe / terrain visualization in the browser.

- https://cesium.com/platform/cesiumjs/

### deck.gl / kepler.gl
Large-scale WebGL data visualization and no-code geospatial exploration.

- https://deck.gl/
- https://kepler.gl/

### Turf.js
Client-side geospatial analysis in JavaScript.

- https://turfjs.org/

### Lonboard
Fast, interactive deck.gl-based vector data visualization in Jupyter, built on GeoArrow/GeoParquet.

- https://developmentseed.org/lonboard/latest/
- https://github.com/developmentseed/lonboard

## Spatial data stack

### GDAL / OGR
Swiss-army knife for raster/vector format conversion and processing.

- https://gdal.org/
- https://github.com/OSGeo/gdal

### PostGIS
Spatial extension for PostgreSQL — storage, indexes, and spatial SQL.

- https://postgis.net/

### DuckDB Spatial
In-process spatial SQL for DuckDB — reads GeoParquet, GDAL formats, and remote files without a server.

- https://duckdb.org/docs/current/core_extensions/spatial/overview

### Apache Sedona
Spatial processing at any scale — SedonaDB (single-node), SedonaSpark, SedonaFlink, and SedonaSnow (Snowflake); vector and raster SQL/Python APIs.

- https://sedona.apache.org/
- https://github.com/apache/sedona

### PROJ
Coordinate reference systems and transformations.

- https://proj.org/

### GeoServer
Open-source server for OGC services (WMS, WFS, WMTS, and more).

- https://geoserver.org/

### Python geospatial
GeoPandas, Shapely, Rasterio, Folium for analysis and quick map notebooks.

- https://geopandas.org/
- https://shapely.readthedocs.io/
- https://rasterio.readthedocs.io/
- https://python-visualization.github.io/folium/latest/

### Formats & tiling

- https://geojson.org/ — GeoJSON
- https://geoparquet.org/ — GeoParquet, columnar geospatial format on Apache Parquet (v2.0 in release-candidate stage)
- https://parquet.apache.org/blog/2026/02/13/native-geospatial-types-in-apache-parquet/ — native GEOMETRY / GEOGRAPHY logical types in Apache Parquet (sometimes called “GeoParquet 2.0”)
- https://geoparquet.io/ — geoparquet-io (`gpio`): CLI + Python API to convert, validate, and optimize GeoParquet (Hilbert sorting, bbox, partitioning)
- https://pmtiles.io/ — single-file PMTiles archives
- https://protomaps.com/ — open map tiles on PMTiles
- https://maplibre.org/maplibre-tile-spec/ — MapLibre Tile (MLT): column-oriented vector tile format, successor to MVT (announced Jan 2026; supported in MapLibre GL JS / Native)
- https://h3geo.org/ — Uber H3 hexagonal hierarchical grid

## Japan / 日本の地理空間情報

### 地理院地図・タイル
国土地理院のベースマップとタイル一覧。出典明示で利用可能なものが多い。

- https://maps.gsi.go.jp/
- https://maps.gsi.go.jp/development/ichiran.html — 地理院タイル一覧

### オープンデータ・基盤
国土数値情報、G空間情報センター、政府オープンデータ、PLATEAU など。

- https://nlftp.mlit.go.jp/ — 国土数値情報ダウンロード
- https://front.geospatial.jp/ — G空間情報センター（ポータル）
- https://www.geospatial.jp/ckan/dataset — G空間情報センター データセット検索
- https://data.e-gov.go.jp/info/ja — e-Govデータポータル（旧 DATA GO JP / data.go.jp、デジタル庁）
- https://www.mlit.go.jp/plateau/ — Project PLATEAU（3D都市モデル）

## Open data & imagery

- https://overturemaps.org/ — Overture Maps Foundation: open global map data (buildings, places, transportation, etc.) distributed as GeoParquet
- https://docs.overturemaps.org/ — Overture schema, release notes, and access guides
- https://www.naturalearthdata.com/ — Natural Earth public-domain cultural/physical data
- https://opentopography.org/ — high-res topography / DEM access
- https://www.gebco.net/ — GEBCO bathymetry
- https://earthengine.google.com/ — Google Earth Engine
- https://developers.google.com/earth-engine
- https://www.hotosm.org/ — Humanitarian OpenStreetMap Team

## .NET / XAML map control

XAML Map Control for WPF / UWP / WinUI map UI.

- https://github.com/ClemensFischer/XAML-Map-Control

## Standards & community

- https://www.ogc.org/ — Open Geospatial Consortium (OGC) (formerly opengeospatial.org, which now redirects here)
- https://felt.com/ — cloud-native, collaborative GIS platform for maps, apps, and dashboards

## Related awesome lists

- https://github.com/osmlab/awesome-openstreetmap
- https://github.com/Esri/awesome-arcgis-developers
