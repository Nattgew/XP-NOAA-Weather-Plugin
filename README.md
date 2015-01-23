# [XPGFS] X-Plane NOAA Global Forecast Weather #

_Original plugin by [Joan](http://joanpc.com)_

*Downloads Forecast data from NOAA servers and sets x-plane wind and cloud layers using forecasted data for the current time and
world coordinates.*

## Requirements ##

[Sandy Barbour Python Interface](http://www.xpluginsdk.org/python_interface_latest_downloads.htm)

[Python 2.7](http://www.python.org/getit/)

Wgrib2: The plugin comes with wgrib2 for common os OSX, win32 and Linux i686 glib2.5

Wgrib uses cygwin on windows but the .dll is provided on the bin folder and there's no need to install-it.

## Installation ##

Install the X-Plane Python interface:

http://www.xpluginsdk.org/python_interface_sdk100_downloads.htm

Copy the zip file contents to your X-Plane/Resources/plugins/PythonScripts folder.

The resulting installation should look like:

`X-Plane/Resources/plugins/PythonScripts/noaaWeatherResources/`

`X-Plane/Resources/plugins/PythonScripts/PI_noaaWeather.py`

`X-Plane/Resources/plugins/PythonScripts/EasyDref.py`

## PATCHES ##

2015 NOAA Patch by [qwerty2k2](http://forums.x-plane.org/index.php?showuser=125293): [Original Post](http://forums.x-plane.org/index.php?showtopic=72313&p=885255), added as of commit _N/A_

## RESOURCES ##

### NOAA: ###

[GFS Products](http://www.nco.ncep.noaa.gov/pmb/products/gfs/)

[GFS Inventory](http://www.nco.ncep.noaa.gov/pmb/products/gfs/gfs.t00z.pgrb2f06.shtml)

[WAFS Inventory](http://www.nco.ncep.noaa.gov/pmb/products/gfs/WAFS_blended_2012010606f06.grib2.shtml)

[NOMADS Filter](http://nomads.ncep.noaa.gov/)

[wgrib2](http://www.cpc.ncep.noaa.gov/products/wesley/wgrib2/)

### OpenGrADS: ###

Interactive desktop tool for easy access, manipulation, and visualization of earth science data and wgrib2 builds for diverse platforms.

[Link](http://sourceforge.net/projects/opengrads/)

### X-Plane: ###

[DATAREFS](http://www.xsquawkbox.net/xpsdk/docs/DataRefs.html)

Some info on what X-Plane does with METAR data: [http://code.google.com/p/fjccuniversalfmc/wiki/Winds](http://code.google.com/p/fjccuniversalfmc/wiki/Winds)