osmtogeojson
============

Converts [OSM](http://openstreetmap.org) [data](http://wiki.openstreetmap.org/wiki/OSM_XML) to [GeoJSON](http://www.geojson.org/).

* fast
* stable
* real OSM [polygon support](https://wiki.openstreetmap.org/wiki/Overpass_turbo/Polygon_Features)
* real OSM multipolygon support
* well [tested](http://github.com/tyrasd/osmtogeojson/blob/master/test/) and proven

This code is used in and maintained by the [overpass turbo](http://github.com/tyrasd/overpass-ide) project.

Usage & API
-----------

nodejs:

    npm install osmtogeojson

    var osm = require('osmtogeojson');
    osm.toGeojson(xml_data);

browser:

    <script src='osm_geojson.js'></script>

    osmtogeojson..toGeojson(xml_data);
