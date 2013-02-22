scrubber.py
===========

Function: Simple regex based script that strips the Canadian census data of the locale and population information, and stores it in a text file.
http://www12.statcan.gc.ca/english/census06/data/popdwell/File.cfm?T=307&SR=1&RPP=699&PR=0&CMA=0&S=3&O=D&LANG=E&OFT=CSV

Usage: 

$$python scrubber.py -s <raw csv data> -d <path of existing destination text file>