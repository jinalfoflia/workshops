# OpenStreetMap - Contribute, validate, extract, analyse and visualise


**16th of Oct** | **NUS, Singapore**

[Jinal Foflia](https://in.linkedin.com/in/jinalfoflia) - fofliajinal@gmail.com | [@fofliajinal](https://twitter.com/fofliajinal)

----

## Contribute

### Getting started with OpenStreetMap

- Sign up [here](https://www.openstreetmap.org/), if you are just getting started with OpenStreetMap

- Introduction to `node(point)`, `way(line)`, and `area(closed polygon)`.

![pasted image at 2017_07_20 10_19 pm](https://user-images.githubusercontent.com/6770741/28456397-c7b56830-6e1f-11e7-9404-3838bfbcbd9e.png)
- How to map buildings. For more: https://www.mapbox.com/mapping/


#### Highway classification

Roads are added with the tag `highway=*`
- Residential roads `highway=residential` - http://wiki.openstreetmap.org/wiki/Tag:highway%3Dresidential
- Service roads  `highway=service` - http://wiki.openstreetmap.org/wiki/Tag:highway%3Dservice
- Paths `highway=path` - http://wiki.openstreetmap.org/wiki/Tag:highway%3Dpath
- Unclassified road`highway=unclassified` - http://wiki.openstreetmap.org/wiki/Tag:highway%3Dunclassified

## Validate

![](https://paper-attachments.dropbox.com/s_CE04567B3697A0F3F978B75306EA9E5323FFA473E314656B8058B743A91AE0E3_1567729482536_image.png)

![](https://paper-attachments.dropbox.com/s_CE04567B3697A0F3F978B75306EA9E5323FFA473E314656B8058B743A91AE0E3_1567729495970_image.png)

![](https://paper-attachments.dropbox.com/s_CE04567B3697A0F3F978B75306EA9E5323FFA473E314656B8058B743A91AE0E3_1567729725837_image.png)

![](https://paper-attachments.dropbox.com/s_CE04567B3697A0F3F978B75306EA9E5323FFA473E314656B8058B743A91AE0E3_1567729745708_image.png)

![](https://paper-attachments.dropbox.com/s_CE04567B3697A0F3F978B75306EA9E5323FFA473E314656B8058B743A91AE0E3_1567729871027_image.png)


[**Vandalism**](https://wiki.openstreetmap.org/wiki/Vandalism) is intentionally ignoring the consensus norms of the OpenStreetMap community. Simple mistakes and editing errors are not vandalism but may need to be reverted using some of the same tools that are used for vandalism.

[**OSM Changeset Analyzer**](http://osmcha.mapbox.com/) or OSMCha is a tool to filter and analyze changesets on OpenStreetMap using the [changeset metadata](https://www.openstreetmap.org/api/0.6/changeset/41775489/download). The tool has a live listing of every changeset on the map, flags potentially suspicious edits and has various filters to find changesets that match a certain criteria. 

Let’s do a hands-on session on how to use OSMCha 

### Other tools for validation
- [OSM-Comments](https://www.mapbox.com/osm-comments/)
- [MapRoulette](http://www.maproulette.org/)
- [HDYC](https://hdyc.neis-one.org/)
- [WHODIDIT](http://simon04.dev.openstreetmap.org/whodidit/)
- [Who’s That](http://whosthat.osmz.ru/)
- [Result Maps](http://resultmaps.neis-one.org/)
- [Missing Maps](https://www.missingmaps.org/users/)
- [Live OSM user stats](http://www.gryph.de:8080/)
- [OSM deep history](https://osmlab.github.io/osm-deep-history)
- [OSM History viewer](http://osmhv.openstreetmap.de/index.jsp)
- [OSM inspector](https://tools.geofabrik.de/osmi/)
- [OSMOSE](http://osmose.openstreetmap.fr/en/map/)
- [Overpass](http://overpass-turbo.eu/)



## Extract

[Overpass turbo](http://overpass-turbo.eu) is a web based [data mining (extracting) tool](https://wiki.openstreetmap.org/wiki/Overpass_turbo) for OpenStreetMap. The source code is found [on github](https://github.com/tyrasd/overpass-turbo). 
 
- Here are the [frequently used](https://github.com/mapbox/mapping/wiki/Overpass:-Frequently-used-queries) overpass queries ([Overpass API/Overpass API by Example
](https://wiki.openstreetmap.org/wiki/Overpass_API/Overpass_API_by_Example))
- Overpass query that we used during the session - https://overpass to extract bus stops in Ahmedabad - turbo.eu/s/wNT
- [Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API) is a read-only API that serves up custom selected parts of the OSM map data.


## Analyse

- [Spatial analysis](https://www.mapbox.com/help/how-analysis-works/) - Spatial analysis includes a variety of techniques and processes used to understand the patterns and relationships of geographic features. Turf, an open source project maintained by Mapbox, is an advanced geospatial JavaScript library that allows you to perform spatial operations in the browser.
- [Turf.js](http://turfjs.org/) - Turf.js is a JavaScript library for spatial analysis. It includes traditional spatial operations, helper functions for creating GeoJSON data, and data classification and statistics tools. Turf can be added to your website as a client-side plugin, or you can [run Turf server-side](https://www.npmjs.com/package/turf) with [Node.js](http://nodejs.org/). You can find the source code on [GitHub](https://github.com/turfjs/turf).
- [Analyze data with Turf.js and Mapbox GL JS](https://www.mapbox.com/help/analysis-with-turf/) - This guide walks through the basics of Turf.js, a JavaScript library used for spatial analysis and statistics, and how to use it to add spatial analysis to your Mapbox GL JS maps.
- [QGIS](https://en.wikipedia.org/wiki/QGIS) - QGIS is a free and open-source cross-platform desktop geographic information system application that supports viewing, editing, and analysis of geospatial data. Find various [tutorials](https://www.qgistutorials.com/en/) related to using QGIS

## Visualise

[Mapbox Studio](https://www.mapbox.com/studio) is your home base for building custom maps with Mapbox. [This manual](https://www.mapbox.com/help/studio-manual/) contains information on how Mapbox Studio works, some guidance on best practices, and a comprehensive application reference.

To get started, you'll only need to sign up to a Mapbox account at [Mapbox.com](https://www.mapbox.com/).


Here are few tutorials from our previous workshops that you can refer to 

- [Webinar: Introduction to Mapbox Studio](https://github.com/mapbox/workshops/tree/gh-pages/HOT-webinar-2017)
- [Workshop: Designing custom maps for your brand](https://github.com/mapbox/workshops/tree/gh-pages/branding-workshop)
- [Futuristic Map Design workshop at Dfrost 2017](https://github.com/mapbox/workshops/tree/gh-pages/dfrost-2017-scifi-map)
- [Instant maps with Cartogram](https://blog.mapbox.com/instant-maps-with-cartogram-5854e65ba4c3)

## Other interesting projects that's used either of the above

- POI finder - https://oini.github.io/poi-finder/
- Chennai Flood Maps - https://osm-in.github.io/flood-map/chennai.html#11.65/13.0493/80.2593
- Railway map - https://shvrm.github.io/railway/#11/50.8783/-355.6201
- Analysis - https://www.townsendjennings.com/maps/
- More about OpenStreetMap - learnosm.org/en/
