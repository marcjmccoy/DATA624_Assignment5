# DATA624_Assignment5
Geoplotlib / geopandas assignment

QUESTION 1) Which are the three cities in BC with the majority of public libraries?

1) most - Vancouver
2) second most - Surrey
3) third most - Langely and Richmond (both have 5)

QUESTION 2) Confirmed with professor that I could use geopandas as opposed to geoplotlib for the choropleth map. The geopandas library does not have the same color palettes (seismic) and tiles (toner-lite). He confirmed I wouldn't get grades reduced for using geopandas. It runs in datascience hub and I added a png for your convenience.

QUESTION 3) Colors do not match perfectly, the ColorMap('jet', alpha=200, levels=20) line would need to be adjusted to be adjusted to match the exact png we were given. I did not know which color palette to use so I just used 'jet'. I also did not know what the levels value should be. The code is set correctly to meet all other requirements outlined in the question. Conidtional statment within to account for the 'lin' vs. 'sqrt' request. Had trouble getting the graphs to next inline (like we talked about on zoom?) for some reason the graphs were fully visible when the panel wsa opened when I used .show() but inline was still cutting the inline picture off even after including your referenced text that you mentioned to include at the top.
