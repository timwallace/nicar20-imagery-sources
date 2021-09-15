# nicar20-imagery-sources
Sources for earth imagery 

## Data and Imagery Viewers
* [Colorado State University RAMMB Slider](https://rammb-slider.cira.colostate.edu)
	* GOES 16/17 and Himawari
* [NOAA View](https://www.nnvl.noaa.gov/view/globaldata.html)
	* Daily ocean, land and atmospheric data
* [NASA Worldview](https://worldview.earthdata.nasa.gov/)
	* Satellite data cornucopia
* [University of Wisconsin-Madison SSEC/CIMSS RealEarth](https://realearth.ssec.wisc.edu/)
	* Satellite data cornucopia
* [Resource Watch](https://resourcewatch.org/data/explore)
	* Hundreds of data sets, many of them climate related
* [Global Forest Watch](https://www.globalforestwatch.org/map)
	* Data and tools for monitoring forests
* [Planet.parts](https://planet.parts/)
	* Curated by [Charlie Loyd](https://twitter.com/vruba/)
	* It is the most comprehensive list of near-realtime Earth observation resources out there.

## Direct data sources

* [**USGS Earth Explorer**](https://earthexplorer.usgs.gov)
  * [Landsat](https://landsat.gsfc.nasa.gov/)
    * Longest-running enterprise for acquisition of satellite imagery of Earth
    * Similar spectral bands make for easier, fairer mapping of change over time 
  * USDA [NAIP](https://www.fsa.usda.gov/programs-and-services/aerial-photography/imagery-programs/naip-imagery/) (US only, no AK or HI 😬)
    * ~1 meter RGB+NIR imagery 
    * New images every two years, starting in roughly 2003
    * Also available [here](https://nrcs.app.box.com/v/naip) 
  * [Sentinel-2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2)
  * [SRTM](https://www2.jpl.nasa.gov/srtm/) as well as other elevation datasets
  * [Declassified](https://www.usgs.gov/science-explorer-results?es=declassified) spy satellite imagery from the 1960s and 1970s. 

* [**NOAA CLASS**](https://www.bou.class.noaa.gov/saa/products/welcome)
  * [VIIRS](https://ncc.nesdis.noaa.gov/VIIRS/)
    * US-only VIIRS for last week [here](ftp://ftp.ssec.wisc.edu/pub/eosdb/npp/viirs/)
  * GOES-R
  * Not the easiest to use
  
* [**Copernicus Open Access Hub**](https://scihub.copernicus.eu/dhus/#/home)
  * Sentinel-1 synthetic-aperture radar
  * Sentinel-2 (like Landsat)
  * Sentinel-3 (like MODIS or VIIRS)
  * [Sentinel-5P](https://earth.esa.int/web/guest/missions/esa-eo-missions/sentinel-5p) (greenhouse gas data)

* [**NASA EARTHDATA**](https://earthdata.nasa.gov/)
  * Countless data products—go hunting!
  * [Alaska Satellite Facility](https://asf.alaska.edu/), a source for current and historic (back to the 1970s!) RADAR data, is available through this login
  
* [**GEO on AWS**](https://registry.opendata.aws/?search=tags:gis,earth%20observation,events,mapping,meteorological,environmental,transportation)
  * Many, many datasets. Here are only a few:
    * [Sentinel-2](https://registry.opendata.aws/sentinel-2/)
    * [Landsat 8](https://landsatonaws.com/)
    * [GOES](https://registry.opendata.aws/noaa-goes/)
    * [Mapzen Terrain Tiles](https://registry.opendata.aws/terrain-tiles/)

## Sources through a platform or company

* [**Google Earth Engine**](https://developers.google.com/earth-engine/datasets/)
  * Too many datasets to list here 
* [**Descartes Labs**](https://www.descarteslabs.com/)
  * Platform access for journalists is in development
  * In the meantime, fire off a note to pr@descarteslabs.com 
  * Better for large scale analysis than access to raw imagery 
  * Examples of work done with journalists: [Foliage](https://www.washingtonpost.com/graphics/2019/national/fall-foliage-atlas/), [Cranberries](https://www.nationalgeographic.com/history/2019/11/united-states-cranberry-harvest-explained-charts/), [Urban Change](https://www.nytimes.com/interactive/2019/12/27/upshot/america-from-above.html)
* [**Planet**](https://www.planet.com/)
  * High temporal resolution
  * Relatively high spatial resolution
  * Relatively low spectral resolution
* [**Maxar**](https://www.maxar.com/)
	* High resolution RGB and synthetic-aperture radar data.
  * Cannot always share 
* [**Iceye**](https://www.iceye.com/)
	* High spatial and temporal resolution synthetic-aperture radar data
* [**Airbus**](https://www.intelligence-airbusds.com/optical-and-radar-data/)
 	* High resolution RGB and synthetic-aperture radar imagery. 
* [**Blacksky**](https://www.blacksky.com/)
  * Plan for high temporal resolution
  * Relatively high spatial resolution
  * Relatively low spectral resolution
  
<sup>P.S. Hate clicking through dozens of links to figure out what the heck I'm talking about? Check out [Joe Morrison's](https://twitter.com/mouthofmorrison) excellent post on [How to Find the Most Recent Satellite Imagery Anywhere on Earth.](https://www.azavea.com/blog/2020/01/02/how-to-find-the-most-recent-satellite-imagery/)<sub>
