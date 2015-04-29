Jaanga Terrain SRTM 30 Plus Read Me
===

<span style=display:none; >[View as web page]( http://jaanga.github.io/terrain-srtm30-plus-r2/terrain-srtm30-plus.html "view the files as apps." ) <input value="<< You are here" size=15 style="font:bold 11pt monospace;border-width:0;" ></span>  

Jaanga Terrain repositories with 'SRTM30 Plus' in the title are a set of repositories with derived data or data viewers that relate to the efforts of the: 

[Scripps Institution of Oceanography]( http://en.wikipedia.org/wiki/Scripps_Institution_of_Oceanography ) at [UCSD]( https://scripps.ucsd.edu/ ).
More specifically, the data is sourced from the Scripps' [Satellite Geodesy]( http://topex.ucsd.edu/index.html ) web site.
And even more specifically to the files relating to the Institution's long-standing effort to supply and maintain a most accurate and most complete 
single source of global bathymetric data based on the [Shuttle Radar Topography Mission (SRTM)]( http://en.wikipedia.org/wiki/Shuttle_Radar_Topography_Mission ).

The Jaanga Terrain repositories include both open data and open source data viewers. Currently the SRTM30 plus data is available in two formats.

* PNG heightmaps organized in [Tile Mapping Service (TMS)]( http://en.wikipedia.org/wiki/Tile_Map_Service ) format.
* PNG heightmaps organized on a 10x10 degree grid format

Apart from sharing a delight with cartography, Jaanga is not in anyway associated with the Scripps Institution of Oceanography.

## Background

The bathymetric data is the result of a lot of research and a lot of work sustained over a period of many years.

Persons involved in the published research and data include::

### Walter H F Smith

* [NOAA STAR]( http://www.star.nesdis.noaa.gov/star/Smith_WHF.php ) << nice video
* [Google Scholar]( https://scholar.google.com/citations?user=Qx0WxlIAAAAJ&hl=en )
* [ResearchGate]( http://www.researchgate.net/profile/Walter_Smith5 )

Co-author of the [Generic Mapping Tools]( http://www.soest.hawaii.edu/gmt/ )

### David T Sandwell

* <http://topex.ucsd.edu/sandwell/>
* [Google Scholar]( https://scholar.google.com/citations?user=qvHZLkEAAAAJ&hl=en )
* [ResearchGate]( http://www.researchgate.net/profile/David_Sandwell )

### Joseph J Becker

* [Google Scholar]( https://scholar.google.com/citations?user=60G-9DsAAAAJ&hl=en )



## Articles

### Global Bathymetry and Elevation Data at 30 Arc Seconds Resolution: SRTM30 PLUS

<http://topex.ucsd.edu/sandwell/publications/124_MG_Becker.pdf>

### Improvement of Marine Gravity and Bathymetry

<ftp://topex.ucsd.edu/pub/sandwell/NGA_proposal/ONR_proposal_9.pdf>


### Global Sea Floor Topography from Satellite Altimetry and Ship Depth Soundings

[Science magazine, Vol 227, 26 September 1997 pp 1956-162](  http://www.luau.ucsd.edu/sandwell/publications/074_Science_predict2.pdf )

#### Abstract

A digital bathymetric map of the oceans with a horizontal resolution of 1 to 12 kilometers was derived by combining available depth soundings with high-resolution marine gravity information from the Geosat and ERS-1 spacecraft. 
Previous global bathymetric maps lacked features such as the 1600-kilometer-long Foundation Seamounts chain in the South Pacific. 
This map shows relations among the distributions of depth, sea floor area, and sea floor age that do not fit the predictions of deterministic models of subsidence
due to lithosphere cooling but may be explained by a stochastic model in which randomly distributed reheating events warm the lithosphere and raise the ocean floor.



### Global Bathymetric Prediction for Ocean Modelling and Marine Geophysics

[topex.ucsd.edu/marine_topo/text/topo.html]( http://topex.ucsd.edu/marine_topo/text/topo.html ) 1996

#### Abstract (partial )

We are constructing a complete bathymetric map of the oceans at a 3-10 km resolution by combining all of the available depth soundings collected over the past 30 years with high resolution marine gravity information provided by the Geosat, ERS-1/2, and Topex/Poseidon altimeters. 
Detailed bathymetry is essential for understanding physical oceanography and marine geophysics. Currents and tides are controlled by the overall shapes of the ocean basins as well as the smaller sharp ocean ridges and seamounts. 
Because erosion rates are low in the deep oceans, detailed bathymetry reveals the mantle convection patterns, the plate boundaries, the cooling/subsidence of the oceanic lithosphere, the oceanic plateaus, and the distribution of off-ridge volcanoes. 
Current global digital bathymetry maps (e.g. ETOPO-5) lack many important details such as a 400 km-long ridge that rises to within 135 m of sea level. 
Moreover, they are contaminated by long-wavelength errors (~2000 km) which prevent accurate identification of seafloor swells associated with mantle plumes [Smith, 1993].

## Data Sources

The elevation data used here has been collected from:

<ftp://topex.ucsd.edu/pub/srtm30_plus/topo30/>

From the Read Me:

>The  subdirectory called topo30 has the data 
	stored in a single large file of 2-byte integers
	in MSB format (i.e. big-endian).  The grid spans 
	0 to 360 in longitude and -90 to 90 in latitude. 
	The upper left corner of the upper left grid cell
	has latitude 90 and longitude 0.  There are 
	43200 columns and 21600 rows. A matching source 
	identification file (SID) called topo30_sid is also 
	included.  The sid numbers are stored as unsigned 
	2-byte integers.

An attempt was made to use the [SRTM15 Plus]( ftp://topex.ucsd.edu/pub/srtm15_plus/ ) data file, but the data appears to be in a different format than the SRTM30 Plus data. 
Further efforts are required in order to decipher this format.


## Data Viewers

[Jaanga Terrain SRTM30 Plus Viewers]( http://jaanga.github.io/terrain-srtm30-plus-viewers/terrain-srtm30-plus-viewers.html ) 

The mission is to be able to view data in 3D as quickly and as easily as possible.

As of this writing, four viewers are supplied. Each only begins to scratch the surface of what is possible.


## Data Derivations

The mission is to help global bathymetric data be readily available to researchers who may have limited programming experience.
The first data set is a collection of PNG heightmaps divided according to the TMS system. 

Data on GitHub:

[TMS 0-7 PNG Files]( https://github.com/jaanga/terrain-srtm30-plus-data-tms-1-7 )

[TMS 7plus PNG Files]( https://github.com/jaanga/terrain-srtm30-plus-data-tms-7plus )
Some details as to why the TMS format is used are detailed in this earlier R1 web pag
e:
[Jaanga Terrain Further Considerations]( http://jaanga.github.io/terrain/readme-reader.html#further-considerations.md ).

The second set of data is in the format of a 10x10 degree grid

[10 Degree PNG Files]( https://github.com/jaanga/terrain-srtm30-plus-data-10degree )

## Code

The tools to gather, parse and store the data are all built in JavaScript with the help of [node.js]( http://nodejs.org ).

All of these tools are available in the [Jaanga Terrain Cookbook]( http://jaanga.github.io/terrain-r2/terrain.html#./cookbook/readme.md# ) along with descriptions and background on the application of the tools. 

## Thanks

See the files listed in the Attributions section of this menu.

See also [Jaanga Terrain Thanks]( http://jaanga.github.io/terrain-r2/terrain.html#thanks.md# ) for more attributions.

'We stand on the shoulders of giants...'



