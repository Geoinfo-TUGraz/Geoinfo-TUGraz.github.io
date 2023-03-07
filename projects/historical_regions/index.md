# Modeling and visualizing the extents of historical regions

---
There are many historical places for which geographical extents are unknown, uncertain, or contested in some combination. Historical scholars from many disciplines in the humanities and social sciences are increasingly trying to map and analyze the geographies of past places, at scales from the urban to the regional, from limited available information. 

This project will focus on historical regions which are geographically vague in a way that their extents are unknown. The cause for this is that these regions are often only mentioned in historical texts that describe their constituent places and their relationships to other places. For example, a historical text may describe settlements in sufficient detail that can be used to deduce their locations and the administrative regions they belong to, but the extents of the administrative regions themselves are not described. This is problematic because it hinders many potential use cases and future research uses of historical data. 

In terms of spatial computation, this is a problem of estimating the geographical extents of a region from locations of geographic entities that are attested to have been within that region. Historical regions will often have shared boundaries with their neighboring regions. In such cases, the inherent uncertainty of an estimated boundary from one region will combine with those of its neighbors. This is where the theory of fuzzy sets can be applied to show that we cannot be certain where one region ends and another starts. 

Another issue is the representation of the uncertainty of geographical information on maps and other cartographic visualization products. GIScience experts are trained to understand that all geographical information comes with a level of spatial uncertainty and may consider this when analyzing maps. However, in digital humanities, the representation of uncertainty becomes more important to prevent the users from misinterpreting the data. 

Historical data also have a temporal component which increases the complexity of boundary estimation and visualization. Historical regions’ constituents may come from different sources and periods, showing how the region’s extents changed over time. This temporal variation also needs to be addressed in the methodology and visualization approach of this project. 

### Colaborators
* Karl Grossner, PhD
* Dr. Eric Delmelle


### Acknowledgements
{%
  include figure.html
  image="images/projects/historical_regions/cagis_logo.avif"
  width="200px"
%}
This project is funded by Cartography and Geographic Information Society.
