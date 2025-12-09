California Wildfire Impact Analysis (2012–2022)

This project visualizes how much of each California county burned in wildfires over a ten-year period. Using wildfire perimeter data and county boundaries, I calculated total acres burned per county and converted it into a percentage of land area burned to compare wildfire impact across the state.

The final result is a graduated map that highlights counties with low to high wildfire exposure.

🔥 Project Workflow

Loaded wildfire perimeters & county boundary layers

Dissolved wildfire polygons into a single footprint

Intersected with county boundaries to isolate burned areas

Calculated burned acreage (US Survey Acres)

Summarized burned area per county

Joined results back to counties & calculated % area burned

Symbolized using 5 Natural Breaks (Jenks) classes

Designed final layout map with labels, legend, scale bar & metadata

🛠 Tools Used

ArcGIS Pro

Dissolve • Intersect • Summary Statistics • Field Calculator

Layout design & export

🗺 Final Map

Percentage of County Area Burned by Wildfires (2012–2022)
