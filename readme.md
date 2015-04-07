Jaanga Terrain SRTM 30 Plus Read Me
===

<span style=display:none; >[View as web page]( http://jaanga.github.io/terrain-srtm30-plus-r2/terrain-srtm30-plus.html "view the files as apps." ) <input value="<< You are here" size=15 style="font:bold 11pt monospace;border-width:0;" ></span>  

Repositories with RTM30 Plus in the title are a set of repositories with derived data or data viewers that relate to the efforts of the 


[Scripps Institution of Oceanography]( http://en.wikipedia.org/wiki/Scripps_Institution_of_Oceanography ) at [UCSD]( https://scripps.ucsd.edu/ ). Includes open data and open source viewers.
More specifically, the data is sourced from the Scripps' [Satellite Geodesy]( http://topex.ucsd.edu/index.html ) web site.
And even more specifically to the Institution's long-standing effort to supply and maintain a most accurate and most complete 
single source of global bathymetric data.


## Data Sources

The data used here has been collected from:

<ftp://topex.ucsd.edu/pub/srtm30_plus/topo30/>

From the Read Me

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

## Data Derivations

The mission is to help global bathymetric data be readily available to researchers who may have limited programming experience.
The first data set is a set of PNG heightmaps divided according to the TMS system. 

Data on GitHub:

[TMS 0-7 PNG Files]( https://github.com/jaanga/terrain-srtm30-plus-data-tms-1-7 )

[TMS 7+ PNG Files]( https://github.com/jaanga/terrain-srtm30-plus-data-tms-7plus )


A derived data set based on the  more standard 1 degree divisions will be made available in due course.


## Data Viewers

The mission is to be able to view data in 3D as quickly and as easily as possible.

As of this writing, four viewers are supplied. Each only begins to scratch the surface of what is possible.






