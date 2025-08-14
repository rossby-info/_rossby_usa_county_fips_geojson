# _rossby_usa_county_fips_geojson

[![](https://img.shields.io/badge/JSON-7.24.25-deeppink.svg?label=usa&#45;counties&#45;min.json)](https://www.rossby.info)
[![](https://img.shields.io/badge/MIT-License-red.svg)](https://opensource.org/license/mit)

## Description

A GEOJSON file for the 50 United States of America:
* To the County FIPS level. (5 digit County FIPS Code.)
* Optimized (Minified) to Precision `4` geo-coordinates (`lon`, `lat`) to improve the file size for better in-browser caching/loading:
  * Example: `-86.8576,31.9622`
  * Stripped of certain meta-data fields to reduce file size.
  * Minified: `8,512 KB`
  * Unminified: `~14,207 KB`
* Each GEO Location has been cross-validated against several other resources to help ensure accuracy.
* Each GEO Location has the following supplemental meta data for use in-broswer (e.g. - GEOJSON [Mapbox](https://www.mapbox.com/) rendering, Google Maps [Markers](https://developers.google.com/maps/documentation/javascript/3d/marker-overview), etc.):
  ```json
  "properties":{
    "geo_point_2d":{"lon":-86.6803,"lat":31.7524},
    "state":"Alabama",
    "short_state":"AL",
    "county":"Butler",
    "fips":"01013"
  }
  ```

## Data Provenance and Use

* Try it out for free at [geojson.io](https://geojson.io)
* In use at [Rossby.info](https://www.rossby.info/)
  * Use the URL: https://raw.githubusercontent.com/rossby-info/_rossby_usa_county_fips_geojson/refs/heads/main/usa.counties.min.geojson
* Converted into JSON, Minified, and modified/altered from:
    * U.S. Census Bureau [Opendatasoft 2023 Counties](https://public.opendatasoft.com/explore/dataset/georef-united-states-of-america-county) (Public Domain, GEOJSON)
* Open Source [MIT License](https://opensource.org/license/mit)

## Resources and Links

* [GitHub](https://github.com/rossby-info/_rossby_usa_county_fips_geojson)
* [Rossby.info](https://www.rossby.info/)
* [Mapbox](https://www.mapbox.com/)
* [Google Maps](https://developers.google.com/maps)
* [geojson.io](https://geojson.io)