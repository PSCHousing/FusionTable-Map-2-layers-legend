FusionTable-Map-2-layers-legend
===============================

Search-and-Filter Map with 2 layers (points and polygons, including dynamic legend), that draws data from Google Fusion Tables, based on template by Derek Eder

Live demo at http://PSCHousing.github.io/FusionTable-Map-2-layers-legend

Use this template if you wish to create a Search-and-Filter map that turns on/off at least 2 layers (points and polygons), with a dynamic legend for the thematic polygons, and draws data from Google Fusion Tables. The default point map displays a textual legend (A, B, C), with option to switch to numeric (0-100) values. The dynamic polygon legend displays a set of three color blocks (modify in custom.css) with different numerical values (modify in maps_lib.js). Based on template customized by Derek Eder http://derekeder.com/searchable_map_template/, with dynamic legend adapted from his http://chicagobuildings.org/

Basic steps:

1) Use Google Fusion Tables to create your point and polygon map layers, and change the feature styles (set ranges, colors, etc.) and info windows.

2) Make your own copy of this template: either Fork to your own GitHub account, or Clone in Desktop, or Download a ZIP compressed version to your desktop.

3) Modify three files, following instructions in the code comments, to match your Google Fusion Table data:

- index.html
- custom.css (located inside the css folder)
- maps_lib.js (located inside the js folder)

3) Host everything on the web (such as a GitHub repository gh-pages branch)

Learn more in an open-access Data Visualization book-in-progress by Jack Dougherty at Trinity College CT
http://epress.trincoll.edu/dataviz
