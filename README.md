# PRISMA2GeoTIFF
Python script to convert he5 PRISMA file to a GeoTIFF.
It is recommended to run this script on a 64-bit python 3.6 version as the 32-bit as a 2Gb memory limit unable to manage huge arrays created from he5 files. A conda environment is probably the best solution to get the correct version of python.
The input is a PRISMA he5 file and the output is a GeoTIFF will all 66 VNIR and 173 SWIR bands. Beware, the last four VNIR bands and the first four SWIR overlap. We will try to add wavelengths description (in nm) to all bands to this script.
