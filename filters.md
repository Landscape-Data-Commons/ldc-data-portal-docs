<!-- This file uses Kramdown-specific syntax and is intended for conversion to HTML with Jekyll's default Markdown converter (Kramdown). As such, it may not render as expected when viewed directly on GitHub due to the HTML tag restrictions of GitHub Flavored Markdown (GFM). -->

{% include navigation.html %}

# Map filters

## Contents
- [Finding](#finding)
- [Selectors](#selectors)
- [Indicators](#indicators)
- [Control Buttons](#control-buttons)
- [Checkbox](#checkbox)

## Finding
Click the filter icon <img src="assets/img/funnel-icon.svg" width="18" class="in-text-icon"> on the sidebar to access the data filters. 
The options on the Selectors and Indicators panels can be used to screen the plots on the map
(see below).

## Selectors
The Selectors panel is shown by default. Selectors are categorical variables such as land-cover type, Ecological Site ID, and state. Choose a selector by clicking the following elements in the given order:
<ol style="margin-top: 10px;">
  <li>The Selectors tab (open by default)</li>
  <li>A selector button in the upper part of the Selectors panel</li>
  <li>The corresponding dropdown that appears in the lower part of the Selectors panel</li>
  <li>A subsequently displayed dropdown option</li>
  <li>The dropdown/autocomplete input for the desired sub-selector (for the 
    Date selector, see below)</li>
</ol>
Next, begin typing in the autocomplete input field. Select the desired field from the 
dropdown list, click the Add/Remove button to create a selection, and then click 
the Submit button. Available selectors are described below.

### Land Cover
Select a land-cover type using the following options:
<ul>
  <li>MODIS IGBP Name</li>
  <li>MODIS IGBP Value</li>
</ul>

### Ecoregion
Select an ecoregion using the following options:
<ul>
  <li>Ecoregion Level I</li>
  <li>Ecoregion Level II</li>
  <li>Ecoregion Level III</li>
  <li>Ecoregion Level IV</li>
</ul>

### MLRA
Select an MLRA using the following options:
<ul>
  <li>MLRA Name</li>
  <li>MLRA Symbol</li>
</ul>

### Ecological Site

Select a type of ecological site using the following options:
<ul>
  <li>Ecological Site ID</li>
  <li>MLRA Prefix (from Ecological Site ID)</li>
  <li>State</li>
</ul>

### State
Select a state using the following option:
<ul>
  <li>US State</li>
</ul>
Currently, only US states are available.

### Project
Select a project using the following option:
<ul>
  <li>Project Name</li>
</ul>

### Date

To select a date range, either (a) drag the range-slider handles or (b) enter dates in the input boxes;
use the following range-slider option:
<ul>
  <li>Date Visited</li>
</ul>

### Data Type
Select a data type (i.e., retrieve only database records that include entries for 
the specified data type that are not NULL) using the following option:
<ul>
  <li>Field Method</li>
</ul>

## Indicators
As described in the second edition of the <a href="https://www.landscapetoolbox.org/wp-content/uploads/2016/02/MMGSSE_20170614.pdf" target="_blank" rel="noopener noreferrer">Jornada Monitoring Manual</a>, indicators include plot measurements such as line-point intercept (e.g., percent bare ground) and vegetation height (e.g., mean woody height) Select data ranges using the dropdown range sliders. Choose an indicator by clicking the following elements in the given order:
<ol style="margin-top: 10px;">
  <li>The Indicators tab</li>
  <li>An indicator button in the upper part of the Indicators panel</li>
  <li>The corresponding dropdown that appears in the lower part of the Indicators panel</li>
  <li>A subsequently displayed dropdown option</li>
</ol> 
To select an indicator range, either (a) drag the range-slider handles or (b) enter indicator
values in the input boxes. Note that each range slider is preset, with the lower handle/value corresponding to the 
mean minus three standard deviations, and the upper handle/value corresponding to the mean plus three standard 
deviations. Available indicators are described below.

###  Line-Point Intercept
Select line-point intercept data ranges using the following indicators:
<ul>
  <li>Percent Bare Ground</li>
  <li>Percent Foliar Cover</li>
  <li>Percent Litter Cover</li>
  <li>Percent Rock Fragment Cover</li>
  <li>Percent Lichen Cover</li>
  <li>Percent Cyanobacteria Cover</li>
</ul>

### Vegetation Height
Select vegetation-height data ranges using the following indicators:
<ul>
  <li>Mean Woody Height</li>
  <li>Mean Herbaceous Height</li>
</ul>

### Canopy Gap
Select canopy gap data ranges using the following indicators:
<ul>
  <li>Canopy Gaps 25-50 cm (%)</li>
  <li>Canopy Gaps 51-100 cm (%)</li>
  <li>Canopy Gaps 101-200 cm (%)</li>
  <li>Canopy Gaps > 200 cm (%)</li>
</ul>

### Soil Stability
Select soil-stability data ranges using the following indicators:
<ul>
  <li>Mean Soil Stability</li>
  <li>Mean Soil Stability: Protected Samples</li>
  <li>Mean Soil Stability: Unprotected Samples</li>
</ul>

## Control Buttons

### Submit Button
Click the Submit button to
<ol>
  <li>Select all plots on the map that satisfy the chosen filter conditions</li>
  <li>Retrieve and populate the tables (that appear below the map) with data
      that satisfy the chosen filter conditions
  </li>
</ol>

### Clear Button
Click the Clear button to
<ol>
  <li>Deselect all selected plots on the map</li>
  <li>Remove the dynamically generated tables below the map</li>
  <li>Return the map layer to the default (Google Terrain)</li>
  <li>Uncheck the <i>Select features from polygon</i> checkbox in the Filters panel</li>
  <li>Remove all chosen selectors and indicators from the Filters panel</li>
</ol>

## Checkbox
Clicking the Submit button with the <i>Select features from polygon</i> 
checkbox checked will (a) show the intersection of filtered plots and polygon-selected plots 
on the map and (b) show the data for the intersection in the tables that appear below the map. 
If no polygon selections exist but filters have been chosen, only the filtered plots 
(and data) are returned. If no filters have been selected but polygon selections exist, the
polygon-selected plots and data are returned. Note that choosing additional filters
and adding polygons with the <i>Select features from polygon</i> checkbox checked will
continue to return the intersection of the filtered plots and polygon-selected plots. Clicking either the 
Clear button in the Filters panel or the Reset button on the map will
uncheck the <i>Select features from polygon</i> checkbox.

