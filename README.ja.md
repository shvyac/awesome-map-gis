# awesome-map-gis（日本語）

[English README](README.md)

地図・GIS の便利なツールとリソース集 — デスクトップ GIS、Web 地図ライブラリ、オープンデータ、クラウドプラットフォーム、日本向けの地理空間情報サービス。

⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。

## OpenStreetMap

クラウドソーシングで作られる世界地図データ、編集ツール、データ抽出。無料のベースマップデータやコミュニティツールはまずここから。

- https://www.openstreetmap.org/
- https://wiki.openstreetmap.org/
- https://overpass-turbo.eu/ — Overpass API の対話型クエリエディタ
- https://www.geofabrik.de/data/download.html — 地域別の OSM データ抽出
- https://nominatim.org/ — OSM ベースのジオコーディング
- https://github.com/osmlab/awesome-openstreetmap ![GitHub stars](https://img.shields.io/github/stars/osmlab/awesome-openstreetmap?style=flat&label=%E2%AD%90)

## デスクトップ GIS

### QGIS
代表的なフリー／オープンソースのデスクトップ GIS — 編集、地図作成、解析、豊富なプラグイン。QGIS 4.0（Qt6 ベース）は 2026年3月にリリース、最新の機能リリースは 4.2（2026年7月）。

- https://qgis.org/
- https://docs.qgis.org/
- https://github.com/qgis/QGIS ![GitHub stars](https://img.shields.io/github/stars/qgis/QGIS?style=flat&label=%E2%AD%90)
- https://changelog.qgis.org/ — リリース変更履歴（4.x 系）

### GRASS（旧 GRASS GIS）
OSGeo のラスター／ベクター解析スイート。2025年に「GRASS」へ名称変更（現行 8.5 系、8.5.0 は 2026年5月リリース）。QGIS の Processing からも利用可能。

- https://grass.osgeo.org/
- https://github.com/OSGeo/grass ![GitHub stars](https://img.shields.io/github/stars/OSGeo/grass?style=flat&label=%E2%AD%90)

### MapWindow Open Source GIS
Windows で使いやすいオープンソースのデスクトップ GIS と関連プロジェクト。Web サイトは更新が止まっている（最終コピーライト 2022年）。ダウンロードとコードは GitHub にある。

- https://www.mapwindow.org/
- https://github.com/MapWindow
- https://github.com/MapWindow/MapWindow5 ![GitHub stars](https://img.shields.io/github/stars/MapWindow/MapWindow5?style=flat&label=%E2%AD%90)

## ArcGIS / Esri

商用 GIS プラットフォーム（デスクトップ、オンライン、開発者向け API）とコミュニティの awesome リスト。

- https://developers.arcgis.com/
- https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview
- https://github.com/Esri/awesome-arcgis-developers ![GitHub stars](https://img.shields.io/github/stars/Esri/awesome-arcgis-developers?style=flat&label=%E2%AD%90)

## クラウド・商用地図プラットフォーム

### Mapbox
ベクタータイル地図、GL SDK、ジオコーディング、ナビゲーション API。

- https://www.mapbox.com/
- https://docs.mapbox.com/

### Google Maps Platform
Maps、Places、Routes などの開発者向け API。

- https://developers.google.com/maps?hl=ja
- https://developers.google.com/maps

### Azure Maps（Bing Maps for Enterprise の後継）
Microsoft の現行の地図／地理空間 API。Bing Maps for Enterprise は非推奨 — Azure Maps へ移行を。

- https://learn.microsoft.com/en-us/azure/azure-maps/
- https://learn.microsoft.com/en-us/azure/azure-maps/migrate-bing-maps-overview

### MapTiler / OpenMapTiles / Stadia / Thunderforest
ホスティング型またはセルフホスト可能なベースマップのタイルとスタイル。

- https://www.maptiler.com/
- https://openmaptiles.org/
- https://stadiamaps.com/
- https://www.thunderforest.com/

### OpenFreeMap
OpenStreetMap ベクタータイルとスタイルを MapLibre 向けに無料配信するオープンソースのサービス — 公開インスタンスは API キー・登録不要で毎週プラネットを更新。スタック一式のセルフホストも可能。

- https://openfreemap.org/
- https://github.com/hyperknot/openfreemap ![GitHub stars](https://img.shields.io/github/stars/hyperknot/openfreemap?style=flat&label=%E2%AD%90)

## Web 地図ライブラリ

### Leaflet
軽量で広く使われている、インタラクティブなラスタータイル地図用 JS ライブラリ。

- https://leafletjs.com/

### MapLibre GL JS
オープンソースの WebGL ベクタータイル地図（Mapbox GL JS のコミュニティフォーク）。現行メジャーバージョンは v6。MVT と新しい MapLibre Tile（MLT）形式の両方に対応。

- https://maplibre.org/
- https://github.com/maplibre/maplibre-gl-js/releases — リリースノート

### OpenLayers
多機能な JS 地図ライブラリ — 投影法、WMS/WFS、編集など、ブラウザでのエンタープライズ GIS。

- https://openlayers.org/

### CesiumJS
ブラウザでの 3D 地球儀／地形の可視化。

- https://cesium.com/platform/cesiumjs/

### deck.gl / kepler.gl
大規模 WebGL データ可視化と、ノーコードの地理空間データ探索。

- https://deck.gl/
- https://kepler.gl/

### Turf.js
JavaScript によるクライアントサイドの地理空間解析。

- https://turfjs.org/

### Lonboard
GeoArrow/GeoParquet を基盤とした、Jupyter 上で高速・インタラクティブな deck.gl ベースのベクターデータ可視化。

- https://developmentseed.org/lonboard/latest/
- https://github.com/developmentseed/lonboard ![GitHub stars](https://img.shields.io/github/stars/developmentseed/lonboard?style=flat&label=%E2%AD%90)

## 空間データスタック

### GDAL / OGR
ラスター／ベクターの形式変換と処理の万能ツール。

- https://gdal.org/
- https://github.com/OSGeo/gdal ![GitHub stars](https://img.shields.io/github/stars/OSGeo/gdal?style=flat&label=%E2%AD%90)

### PostGIS
PostgreSQL の空間拡張 — 格納、インデックス、空間 SQL。

- https://postgis.net/

### DuckDB Spatial
DuckDB のインプロセス空間 SQL — サーバー不要で GeoParquet、GDAL 対応形式、リモートファイルを読み込める。

- https://duckdb.org/docs/current/core_extensions/spatial/overview

### Apache Sedona
あらゆる規模の空間処理 — SedonaDB（シングルノード）、SedonaSpark、SedonaFlink、SedonaSnow（Snowflake）。ベクター／ラスターの SQL・Python API。

- https://sedona.apache.org/
- https://github.com/apache/sedona ![GitHub stars](https://img.shields.io/github/stars/apache/sedona?style=flat&label=%E2%AD%90)

### PROJ
座標参照系と座標変換。

- https://proj.org/

### GeoServer
OGC サービス（WMS、WFS、WMTS など）を提供するオープンソースのサーバー。

- https://geoserver.org/

### Martin
MapLibre プロジェクトの高速な Rust 製ベクタータイルサーバー — PostGIS のテーブル／関数、PMTiles、MBTiles、COG、GeoJSON、GeoParquet を配信。タイル生成用の `martin-cp` と `mbtiles` ツールも同梱。

- https://maplibre.org/martin/
- https://github.com/maplibre/martin ![GitHub stars](https://img.shields.io/github/stars/maplibre/martin?style=flat&label=%E2%AD%90)

### Python 地理空間ライブラリ
解析や手軽な地図ノートブック向けの GeoPandas、Shapely、Rasterio、Folium。

- https://geopandas.org/
- https://shapely.readthedocs.io/
- https://rasterio.readthedocs.io/
- https://python-visualization.github.io/folium/latest/

### フォーマットとタイル

- https://geojson.org/ — GeoJSON
- https://geoparquet.org/ — GeoParquet：Apache Parquet 上の列指向地理空間フォーマット（v2.0 はリリース候補段階）
- https://parquet.apache.org/blog/2026/02/13/native-geospatial-types-in-apache-parquet/ — Apache Parquet ネイティブの GEOMETRY / GEOGRAPHY 論理型（「GeoParquet 2.0」と呼ばれることも）
- https://geoparquet.io/ — geoparquet-io（`gpio`）：GeoParquet の変換・検証・最適化（Hilbert ソート、bbox、パーティショニング）を行う CLI + Python API
- https://pmtiles.io/ — 単一ファイルの PMTiles アーカイブ
- https://protomaps.com/ — PMTiles によるオープンな地図タイル
- https://maplibre.org/maplibre-tile-spec/ — MapLibre Tile（MLT）：MVT の後継となる列指向ベクタータイル形式（2026年1月発表、MapLibre GL JS / Native が対応）
- https://h3geo.org/ — Uber H3 六角形階層グリッド
- https://stacspec.org/ — STAC（SpatioTemporal Asset Catalog）：衛星画像などの地理空間アセットを記述・検索するための共通 JSON 仕様（v1.1、OGC Community Standard でもある）
- https://github.com/radiantearth/stac-spec ![GitHub stars](https://img.shields.io/github/stars/radiantearth/stac-spec?style=flat&label=%E2%AD%90)

## 日本の地理空間情報

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

## オープンデータと画像

- https://overturemaps.org/ — Overture Maps Foundation：GeoParquet で配布される全球のオープン地図データ（建物、施設（places）、交通など）
- https://docs.overturemaps.org/ — Overture のスキーマ、リリースノート、アクセスガイド
- https://www.naturalearthdata.com/ — Natural Earth：パブリックドメインの人文・自然データ
- https://opentopography.org/ — 高解像度地形データ／DEM へのアクセス
- https://www.gebco.net/ — GEBCO 海底地形
- https://mapterhorn.com/ — Mapterhorn：Web 地図向けに PMTiles で配布される全球のオープン地形（標高）タイル（MapLibre の地形表示・陰影起伏）
- https://github.com/mapterhorn/mapterhorn ![GitHub stars](https://img.shields.io/github/stars/mapterhorn/mapterhorn?style=flat&label=%E2%AD%90)
- https://earthengine.google.com/ — Google Earth Engine
- https://developers.google.com/earth-engine
- https://www.hotosm.org/ — Humanitarian OpenStreetMap Team

## .NET / XAML 地図コントロール

WPF / UWP / WinUI の地図 UI 向け XAML Map Control。

- https://github.com/ClemensFischer/XAML-Map-Control ![GitHub stars](https://img.shields.io/github/stars/ClemensFischer/XAML-Map-Control?style=flat&label=%E2%AD%90)

## 標準化とコミュニティ

- https://www.ogc.org/ — Open Geospatial Consortium（OGC）（旧 opengeospatial.org、現在はこちらへリダイレクト）
- https://felt.com/ — 地図・アプリ・ダッシュボードを共同編集できるクラウドネイティブな GIS プラットフォーム

## 関連する awesome リスト

- https://github.com/osmlab/awesome-openstreetmap ![GitHub stars](https://img.shields.io/github/stars/osmlab/awesome-openstreetmap?style=flat&label=%E2%AD%90)
- https://github.com/Esri/awesome-arcgis-developers ![GitHub stars](https://img.shields.io/github/stars/Esri/awesome-arcgis-developers?style=flat&label=%E2%AD%90)

## shvyac の awesome リスト

[shvyac](https://github.com/shvyac) が管理しているキュレーションリストの一覧:

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
