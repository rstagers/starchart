# chart.py

Python program to generate star charts. Currently supports creating charts in the following projections:
* stereographic - for generating atlas style maps covering large areas of sky.
* gnomonic - for generating field of view type charts useful as finder charts.
* polar - for generating a polar view.

see `generate_charts.bat` for sample script to generate low res 'index' charts and high res
starmaps.

The program uses data from the Tycho2 catalogue: http://cdsarc.u-strasbg.fr/viz-bin/Cat?I/259 and 
the Revised New General Catalogue: http://www.klima-luft.de/steinicke/ngcic/rev2000/Explan.htm.

There are quite a few options which are documented in the program:

`python chart.py --help`

I have a version of the tycho2 catalogue here: <https://dl.dropboxusercontent.com/u/5315243/starchart/tycho2_abbr_new2.dat>
