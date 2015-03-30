This gist shows a map of Washington, D.C. divided into census tracts.  Each tract is shaded according to the owner occupancy % for all households.  Points of interest are indicated as red dots.  A key in the lower left shows the quantize thresholds associated with each shade.  

Shapefiles came from census.gov TIGER files.  Owner occupancy data came from the 2012 5-year American Community Survey of the US Census.  Points come from Ben Balter's map of D.C. bars (shots are likely to have been taken at these locations).

Map projection scale created dynamically by code from Bostock's [New Jersey State Plane](http://bl.ocks.org/mbostock/5126418) block.

Shading key element is Bostock's [Threshold Key](http://bl.ocks.org/mbostock/4573883) block, adapted for d3.quantize().