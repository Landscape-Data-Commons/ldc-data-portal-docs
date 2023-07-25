<!-- This file uses Kramdown-specific syntax and is intended for conversion to HTML with Jekyll's default Markdown converter (Kramdown). As such, it may not render as expected when viewed directly on GitHub due to the HTML tag restrictions of GitHub Flavored Markdown (GFM). -->

{% include navigation.html %}

# Map controls
- [Finding](#finding)
- [Zoom (+/-) Control](#zoom---control)
- [Zoom Slider](#zoom-slider)
- [Polygon Selector/Deselector](#polygon-selectordeselector)
- [Map-layer Selector](#map-layer-selector)
- [Reset Button](#reset-button)

## Finding
The 5 map controls are located on the right-hand side of the data-portal map: 

## Zoom (+/-) Control
The zoom buttons allow users to incrementally zoom in and out by clicking the 
plus (+) button and the minus (-) button, respectively.

## Zoom Slider
Use the zoom slider to quickly zoom in and out.

## Polygon Selector/Deselector
Clicking the polygon button (the button with the polygon icon <img src="assets/img/polygon-icon.svg" width="20">) produces a submenu with Select and Deselect options. 
Drawing a polygon with the Select option adds plots to the total set of selected plots 
(polygon selections are additive). Drawing a polygon with the Deselect option removes plots
from the selection set.

## Map-Layer Selector
Clicking the map-layer button (the button with the map-layers icon <img src="assets/img/map-layers-icon.svg" width="20" >) produces a menu with 4 Google 
map-layer options: 
<ol>
  <li>Terrain (the default)</li>
  <li>Satellite</li>
  <li>Road</li>
  <li>Hybrid</li>
</ol>
Clicking the Clear button on the Filters sidebar panel or the
Reset button on the map will reset the map layer to Google Terrain.

## Reset Button
Click the Reset button <img src="assets/img/reset-icon.svg" width="18" class="in-text-icon in-text-reset-icon "> to do the following:
<ol>
  <li>Deselect all selected plots on the map</li>
  <li>Remove the dynamically generated tables below the map</li>
  <li>Return the map layer to the default (Google Terrain)</li>
  <li>Uncheck the <i>Select features from polygon</i> checkbox on the Filters panel</li>
</ol>
Note that the Reset button acts like the Clear button on 
the Filters panel &#8212; with one important difference: the Reset button does <b>not</b> deselect
chosen selectors and indicators.
