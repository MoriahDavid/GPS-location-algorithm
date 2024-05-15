# Autonomous Robotics Course
## Ex0 - GNSS Raw Measurements :world_map: :earth_africa:
This assignment focuses on the basic principles of GNSS and we asked to implement a naive positioning algorithm based on RMS (Root Mean Square) of selected (i.e., weighted) pseudo-ranges.

### Our Positioning Algorithm: :globe_with_meridians:
The algorithm estimates the position of a GPS receiver using raw data from multiple satellites, leveraging the least squares optimization method.<br /> The core of the algorithm is a weighted least squares optimization, where the differences between observed and calculated pseudo-ranges are minimized. values are weighted by the square root of the normalized CN0 values, giving more importance to higher-quality signals. <br />The result of the algorithm provides an estimated ECEF position (X, Y, Z) of the GPS receiver and the clock bias.

### How to run? :receipt:
Open the project in Colab <br />
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MoriahDavid/GPS-location-algorithm/blob/main/gps.ipynb) Click to open and run.<br />
Run the preparation section. <br />
In the solution section, choose the file type you want to run and continue running all the cells.<br />
In the end, the map will be shown and you can see the locations that calculated using our algorithm.
In addition, the map can present also the points that are calculated in the GPS receiver.<br />


The points on the map:<br />
![image](https://github.com/MoriahDavid/GPS-location-algorithm/assets/93945532/dafb164b-f64f-40f1-aac2-99e79c798972)

<br />
Additional information on a specific point can presented by clicking on it:<br />

![image](https://github.com/MoriahDavid/GPS-location-algorithm/assets/93945532/931f78c0-0c92-4fed-ae61-8a309f0e6f03)

<br />
Compare our algorithm to the GPS receiver:<br />

![image](https://github.com/MoriahDavid/GPS-location-algorithm/assets/93945532/53b6cd80-af21-42c2-b3da-78bd7790e377)

