# HeatMapWithTime

* HeatMapWithTime: Heatmap with Leaflet.TimeDimension (based on folium.plugins.HeatMapWithTime)
* MarkerStyleWithTime:
  * Change radius of circle marker with Leaflet.TimeDimension (based on folium.plugins.TimestampedGeoJson)
  * Line chart in marker popup

## HeatMapWithTime
* [heatmapwithtime.html](https://deton.github.io/HeatMapWithTime/heatmapwithtime.html?latlon=35.5403,139.6987&jsonurl=https://deton.github.io/HeatMapWithTime/sampledata/15-PT30M.json)
* [Show diff data](https://deton.github.io/HeatMapWithTime/heatmapwithtime.html?latlon=35.5403,139.6987&negative=1&jsonurl=https://deton.github.io/HeatMapWithTime/sampledata/15-PT30M_diff.json)

## MarkerStyleWithTime
* [MarkerStyleWithTime.html](https://deton.github.io/HeatMapWithTime/MarkerStyleWithTime.html?latlon=35.5403,139.6987&jsonurl=https://deton.github.io/HeatMapWithTime/sampledata/15-PT30M.geojson)

## Other files
* [gbfshist2heatmap.html](https://deton.github.io/HeatMapWithTime/gbfshist2heatmap.html): Make heatmap json for heatmapwithtime.html from gbfshist.ndjson
  * Sample input: sampledata/15-PT30M.ndjson
  * Sample output: sampledata/15-PT30M.json
* [heatmapdiffdata.html](https://deton.github.io/HeatMapWithTime/heatmapdiffdata.html): Make diff data json for heatmapwithtime.html from heatmap json
  * Sample input: sampledata/15-PT30M.json
  * Sample output: sampledata/15-PT30M_diff.json
* [gbfshist2TimestampedGeoJson.html](https://deton.github.io/HeatMapWithTime/gbfshist2TimestampedGeoJson.html): Make geojson for MarkerStyleWithTime.html from gbfshist.ndjson
  * Sample input: sampledata/15-PT30M.ndjson
  * Sample output: sampledata/15-PT30M.geojson
* fetchGbfs.gs: Google Apps Script to fetch GBFS files and save gbfshist.ndjson (run every 5 minutes)
  * Sample output: sampledata/15-PT30M.ndjson

## License
* html files are distributed under the terms of the MIT license.
* sample data used in the demo:
  * This sample data uses the following copyrighted material with modifications.
    * DOCOMO BIKESHARE, INC. / Association for Open Data of Public Transportation, [Bikeshare information of DOCOMO BIKESHARE, INC.](https://ckan.odpt.org/dataset/c_bikeshare_gbfs-d-nationwide-bikeshare), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en).
    * OpenStreet Corp. / Association for Open Data of Public Transportation, [Bikeshare information of OpenStreet](https://ckan.odpt.org/dataset/c_bikeshare_gbfs-openstreet), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en), [ODC BY 1.0](https://opendatacommons.org/licenses/by/1-0/), [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
