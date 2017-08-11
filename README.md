# Pentaho WAQR (Web Adhoc Query and Reporting) Plugin
This is an unofficial & built fork of Pentaho's legacy [WAQR (Web Adhoc Query and Reporting)](http://source.pentaho.org/svnroot/platform-plugins/waqr-plugin/trunk/), patched so that it works in Pentaho 7.0+

There was a change in the way Pentaho was passing URL paths to WAQR that broke WAQR so that it wasn't able load any saved files. This fork (see [5bf17c8](https://github.com/DeBortoliWines/pentaho-waqr-plugin/commit/5bf17c889b174ff61b5a7b968bf4133fd8a86744)) fixes that problem.

# Installation
This is prebuilt, so all you have to do is clone this to your `pentaho-solutions/system` directory:

`$ git clone https://github.com/DeBortoliWines/pentaho-waqr-plugin waqr`
