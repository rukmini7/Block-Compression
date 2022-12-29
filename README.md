# Block Compression Use Case.
# A set of co-ordinates list will be give, which has the x co-ordinate lower end point and x co-ordinate higher end point.
# The same co-ordinates set will also have y co-ordinate lower end point and y co-ordinate higher end point.
# The data set also has compressibility factor.
# I will filter out the co-ordinates which has compressibility factor more than 50%
# # I will then calculate the delta of the co-ordinates, find the x start and end point, y start and end points and plot the polygons (rectangles in this case)
# Post calculation of the co-ordinates polygons will be plotted using the Geometry module from the Shapely python package
# I further used the Geopandas library and used the Union operation upon the plotted polygons to acheive the compressibility by unioning the nearby polygons and forming it into a single polygon thereby to save the area.



# The code has 2 input dataset, horizontal and vertical Co-ordinates list along with Compressibility factors.
# a single jupyter notebook Blockcompression.ipynb