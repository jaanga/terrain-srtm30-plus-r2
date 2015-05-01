Jaanga Terrain SRTM30 Plus Read Me
===

<span style=display:none; >[View as web page]( http://jaanga.github.io/terrain-srtm30-plus-r2/terrain-srtm30-plus.html "view the files as apps." ) <input value="<< You are here" size=15 style="font:bold 11pt monospace;border-width:0;" ></span>  

Jaanga Terrain repositories with 'SRTM30 Plus' in the title are a set of GitHub repositories with derived data or data viewers 
that relate to the [SRTM30 Plus Global Bathymetry project]( http://topex.ucsd.edu/WWW_html/srtm30_plus.html ) at the [Scripps Institution of Oceanography]( http://en.wikipedia.org/wiki/Scripps_Institution_of_Oceanography ) 
at [UCSD]( https://scripps.ucsd.edu/ ) along with the [NOAA]( http://www.noaa.gov/ ), [US Navy]( https://www.navy.com ), [NGA]( https://www.nga.mil/ ), [GEBCO]( http://www.gebco.net/ )

Full project references, links to papers and more: [SRTM30 Plus Attributions and Background]( http://jaanga.github.io/terrain-srtm30-plus-r2/terrain-srtm30-plus.html#attributions-background.md# )

The Jaanga Terrain repositories include both open data and open source data viewers. 
Currently the SRTM30 plus data is available in two formats.

* PNG heightmaps organized in [Tile Mapping Service (TMS)]( http://en.wikipedia.org/wiki/Tile_Map_Service ) format.
* PNG heightmaps organized in a [10x10 degree grid format]( https://github.com/jaanga/terrain-srtm30-plus-data-10degree )

Apart from sharing a deep delight with bathymetry, Jaanga is not in anyway associated with the Scripps Institution of Oceanography.


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

Data: SIO, NOAA, US Navy, NGA, GEBCO

## Code

The tools to gather, parse and store the data are all built in JavaScript with the help of [node.js]( http://nodejs.org ).

All of these tools are available in the [Jaanga Terrain Cookbook]( http://jaanga.github.io/terrain-r2/terrain.html#./cookbook/readme.md# ) along with descriptions and background on the application of the tools. 

## Thanks

See the files listed in the Attributions section of this menu.

See also [Jaanga Terrain Thanks]( http://jaanga.github.io/terrain-r2/terrain.html#thanks.md# ) for more attributions.

'We stand on the shoulders of giants...'



