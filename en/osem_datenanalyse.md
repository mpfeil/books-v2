# Data analysis {#head}

## Interpolation

In the tab _Interpolation_ the data of several senseBoxes can be spatially interpolated to a phenomenon.

This is useful to make the spatial differences of a phenomenon visible on the map, or to derive approximate values in regions where no sensors are present.

<img src="https://raw.githubusercontent.com/sensebox/resources/master/images/osem_interpolation.jpg" center width="700px" />

The interpolation method **IDW** (_Inverse Distance Weighting_) is used, which has a _power_ value as parameter. This is the exponent with which the distance of a measured value to a location to be interpolated is weighted.
A low value for _power_ thus includes values from greater distances as strongly as from close range, while a high value for _power_ especially considers values from immediate distance.

After setting the parameters, the interpolation is calculated on our server.
When the calculation is complete, the result is displayed as a heat map on the map.
The cell size of the calculation can also be set to get more detailed results, but please note that the calculation time for smaller cells increases considerably.
