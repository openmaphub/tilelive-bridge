# Changlog

## 2.2.0

 - Render VTs with strictly_simple flag.

## 2.1.0

 - Reduce default simplify_distance to 4 targeting GL rendering.

## 2.0.0

 - Update to new carmen geocoder indexing API.

## 1.6.0

 - Return a header that will notify tilelive if vector data is painted.

## 1.5.1

 - Removed bad checked if image is painted to determine if it is empty or not as this
   results in empty tiles being created.

## 1.5.0

 - Update to mapnik 3.4.6

## 1.4.0

 - Update to mapnik 3.4.x.

## 1.3.0

 - Update to mapnik 3.3.x with improved VT simplification.

## 1.2.6

 - Drain the mapnik-pool before destroying it during .close()
 
## 1.2.5

 - Rollback getIndexableDocs limit change

## 1.2.4

 - Fix bug with getIndexableDocs bbox generation

## 1.2.3

 - Double tap interpolation (missed parity flag)

## 1.2.2

 - Handle interpolation keys when indexing carmen docs

## 1.2.1

 - Fix for edgecase bug in pixel_key generation
 - Remove check for xml differences before updating map

## 1.2.0

 - Update to node-mapnik@3.1.0
 - Automatically reproject data to WGS84 in geIndexableDocs

## 1.1.0

 - More efficient featureset iteration in getIndexableDocs from @manubb
 - Drop tolerance for vector tile encoding to 8 to better support GL rendering

## 1.0.0

 - Update to node-mapnik@3.0.0, requires C++11 support.

## 0.6.0

 - Non-optional gzip compression for output VTs

## 0.5.0

 - Add basic handling for raster sources

## 0.4.0

 - Adjust tolerance from sliding scale to constant 32 until maxzoom is reached

## 0.3.0

 - Loosen node-mapnik semver to any ~1.4.0 version
 - Drop eio in favor of node 0.10+ UV_THREADPOOL_SIZE

## 0.2.0

 - Update to node-mapnik 1.4.x binaries! \o/

## 0.1.0

 - Update to node-mapnik 1.3.x series.

## 0.0.6

 - Adds support for carmen (dev) getIndexableDocs method.
 - Fixes tile solid handling.

## 0.0.5

 - Flipped default handling of solid tiles from blank: true to blank: false.

## 0.0.4

 - Fix handling of buffer to work with node-mapnik v1.2.x changes (#5)

## 0.0.3

 - Bumped node-mapnik dep to v1.2.x
 - Added LICENSE
 - Added travis support
