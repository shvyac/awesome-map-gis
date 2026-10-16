# awesome-map-gis

[日本語 README](README.ja.md)

Useful maps / GIS tools and resources — desktop GIS, web mapping libraries, open data, cloud platforms, and Japan-focused geospatial services.

⭐ badges show live GitHub star counts (via shields.io).

## OpenStreetMap

Crowd-sourced world map data, editing tools, and extracts. Start here for free basemap data and community tooling.

- https://www.openstreetmap.org/
- https://wiki.openstreetmap.org/
- https://overpass-turbo.eu/ — interactive Overpass API query editor
- https://www.geofabrik.de/data/download.html — regional OSM extracts
- https://nominatim.org/ — OSM-based geocoding
- https://github.com/osmlab/awesome-openstreetmap ![GitHub stars](https://img.shields.io/github/stars/osmlab/awesome-openstreetmap?style=flat&label=%E2%AD%90)

## Desktop GIS

### QGIS
Leading free/open-source desktop GIS — editing, cartography, analysis, and a large plugin ecosystem. QGIS 4.0 (Qt6-based) was released in March 2026; the latest feature release is 4.2 (July 2026).

- https://qgis.org/
- https://docs.qgis.org/
- https://github.com/qgis/QGIS ![GitHub stars](https://img.shields.io/github/stars/qgis/QGIS?style=flat&label=%E2%AD%90)
- https://changelog.qgis.org/ — release changelogs (4.x series)

### GRASS (formerly GRASS GIS)
OSGeo raster/vector analysis suite, rebranded as “GRASS” in 2025 (current series 8.5; 8.5.0 released May 2026); also available via QGIS Processing.

- https://grass.osgeo.org/
- https://github.com/OSGeo/grass ![GitHub stars](https://img.shields.io/github/stars/OSGeo/grass?style=flat&label=%E2%AD%90)

### MapWindow Open Source GIS
Windows-friendly open-source GIS desktop and related projects. The website is no longer actively updated (last copyright 2022); downloads and code are on GitHub.

- https://www.mapwindow.org/
- https://github.com/MapWindow
- https://github.com/MapWindow/MapWindow5 ![GitHub stars](https://img.shields.io/github/stars/MapWindow/MapWindow5?style=flat&label=%E2%AD%90)

## ArcGIS / Esri

Commercial GIS platform (desktop, online, developer APIs) and community awesome list.

- https://developers.arcgis.com/
- https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview
- https://github.com/Esri/awesome-arcgis-developers ![GitHub stars](https://img.shields.io/github/stars/Esri/awesome-arcgis-developers?style=flat&label=%E2%AD%90)

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

### OpenFreeMap
Free, open-source hosting of OpenStreetMap vector tiles and styles for MapLibre — public instance with no API key or registration, weekly planet updates, or self-host the whole stack.

- https://openfreemap.org/
- https://github.com/hyperknot/openfreemap ![GitHub stars](https://img.shields.io/github/stars/hyperknot/openfreemap?style=flat&label=%E2%AD%90)

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
- https://github.com/developmentseed/lonboard ![GitHub stars](https://img.shields.io/github/stars/developmentseed/lonboard?style=flat&label=%E2%AD%90)

## Spatial data stack

### GDAL / OGR
Swiss-army knife for raster/vector format conversion and processing.

- https://gdal.org/
- https://github.com/OSGeo/gdal ![GitHub stars](https://img.shields.io/github/stars/OSGeo/gdal?style=flat&label=%E2%AD%90)

### PostGIS
Spatial extension for PostgreSQL — storage, indexes, and spatial SQL.

- https://postgis.net/

### DuckDB Spatial
In-process spatial SQL for DuckDB — reads GeoParquet, GDAL formats, and remote files without a server.

- https://duckdb.org/docs/current/core_extensions/spatial/overview

### Apache Sedona
Spatial processing at any scale — SedonaDB (single-node), SedonaSpark, SedonaFlink, and SedonaSnow (Snowflake); vector and raster SQL/Python APIs.

- https://sedona.apache.org/
- https://github.com/apache/sedona ![GitHub stars](https://img.shields.io/github/stars/apache/sedona?style=flat&label=%E2%AD%90)

### PROJ
Coordinate reference systems and transformations.

- https://proj.org/

### GeoServer
Open-source server for OGC services (WMS, WFS, WMTS, and more).

- https://geoserver.org/

### Martin
Fast Rust vector-tile server from the MapLibre project — serves PostGIS tables/functions, PMTiles, MBTiles, COG, GeoJSON, and GeoParquet; includes `martin-cp` for tile generation and `mbtiles` tooling.

- https://maplibre.org/martin/
- https://github.com/maplibre/martin ![GitHub stars](https://img.shields.io/github/stars/maplibre/martin?style=flat&label=%E2%AD%90)

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
- https://stacspec.org/ — STAC (SpatioTemporal Asset Catalog): common JSON spec for describing and searching satellite imagery and other geospatial assets (v1.1; also an OGC Community Standard)
- https://github.com/radiantearth/stac-spec ![GitHub stars](https://img.shields.io/github/stars/radiantearth/stac-spec?style=flat&label=%E2%AD%90)

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
- https://mapterhorn.com/ — Mapterhorn: open-data global terrain (elevation) tiles distributed as PMTiles for web maps (MapLibre terrain / hillshading)
- https://github.com/mapterhorn/mapterhorn ![GitHub stars](https://img.shields.io/github/stars/mapterhorn/mapterhorn?style=flat&label=%E2%AD%90)
- https://earthengine.google.com/ — Google Earth Engine
- https://developers.google.com/earth-engine
- https://www.hotosm.org/ — Humanitarian OpenStreetMap Team

## .NET / XAML map control

XAML Map Control for WPF / UWP / WinUI map UI.

- https://github.com/ClemensFischer/XAML-Map-Control ![GitHub stars](https://img.shields.io/github/stars/ClemensFischer/XAML-Map-Control?style=flat&label=%E2%AD%90)

## Standards & community

- https://www.ogc.org/ — Open Geospatial Consortium (OGC) (formerly opengeospatial.org, which now redirects here)
- https://felt.com/ — cloud-native, collaborative GIS platform for maps, apps, and dashboards

## Related awesome lists

- https://github.com/osmlab/awesome-openstreetmap ![GitHub stars](https://img.shields.io/github/stars/osmlab/awesome-openstreetmap?style=flat&label=%E2%AD%90)
- https://github.com/Esri/awesome-arcgis-developers ![GitHub stars](https://img.shields.io/github/stars/Esri/awesome-arcgis-developers?style=flat&label=%E2%AD%90)

## shvyac's awesome lists

All curated lists maintained by [shvyac](https://github.com/shvyac):

- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
