# Autonomous Robotics Course
## Ex0 - GNSS Raw Mesurments :world_map: :earth_africa:
This assignment focuses on the basic principles of GNSS and we asked to implement a naive positioning algorithm based on RMS (Root Mean Square) of selected (i.e., weighted) pseudo-ranges.

### Our Positioning Algorithm: :globe_with_meridians:
The algorithm estimates the position of a GPS receiver using raw data from multiple satellites, leveraging the least squares optimization method.<br /> The core of the algorithm is a weighted least squares optimization, where the differences between observed and calculated pseudo-ranges are minimized. values are weighted by the square root of the normalized CN0 values, giving more importance to higher-quality signals. <br />The result of the algorithm provides an estimated ECEF position (X, Y, Z) of the GPS receiver and the clock bias.

### How to run? :receipt:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MoriahDavid/GPS-location-algorithm/blob/main/gps.ipynb) Open the project in Colab<br />
Run the preparation section. <br />
In the solution section, choose the file type you are interested in running and continue running all the cells.<br />
