# Pointclouds (Stefan) 

Most of the pointcloud work at the center was done 2 years ago, I want to check if that software is still working.
 
- At the first sprint I want to work towards a new version of http://ahn2.pointclouds.nl/ with the more detailed ahn3 data set (https://www.pdok.nl/nl/ahn3-downloads). To do this we will need to construct a octree from a subset of the ahn3 datafiles using https://github.com/NLeSC/Massive-PotreeConverter.

- After that we will use https://github.com/NLeSC/ahn-pointcloud-viewer to visualize the octree.

- Finally run the https://github.com/NLeSC/ahn-pointcloud-viewer-ws web service so users can extract points.

We will approach the 3 repos as a developer who has just found http://ahn2.pointclouds.nl/ and wants to re-use the visualization for his/her own data. During the 3 steps we will update the documentation, build infrastructure and code where needed.
 
The second sprint I want to follow the tutorials of the photogrammetry pipelines: https://github.com/NLeSC/structure-from-motion and
https://github.com/ImproPhoto/pymicmac. By testing these tutorials we will most likely run into problems, will improve the tutorial, installation documentation while solving these problems.

The third sprint I want to follow the tutorials for pointcloud analysis https://github.com/NLeSC/PattyAnalytics and https://github.com/NLeSC/python-pcl. PattyAnalyitcs has tools for segmentation and registration. Python-cl is used as a dependency in PattyAnalytics. https://github.com/NLeSC/python-pcl is a fork, let's catch up with the upstream repo (https://github.com/strawlab/python-pcl) and see if any of the improvements in the fork can be changed into pull requests for the upstream repo. The python-pcl is a Cython wrapper around the [pcl library](http://pointclouds.org/) so it requires at least one team member with Cython knowledge to work on it.

We also want to have a pointcloud viewer integrate into Regis https://github.com/ReGIS-org/regis, clicking a polygon in a 2d map should show the pointcloud of that area. This would give the the https://github.com/eEcoLiDAR project a boost.

