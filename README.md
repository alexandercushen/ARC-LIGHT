# ARC-LIGHT
Repo for ML python scripts for Human Lander Challenge project

optical_depth_cnn.ipynb is the current main workbook. In this file our goal is to construct a CNN which takes a camera image (of the inside of SELENE, when mist is present) and return the optical depth of the scene. This data can then be used to infer the interference on the lidar scan, which is unable to detect the tank base as the mist increases. By determining the optical depth, we can then back out the true distance to the tank base and the obstacles present there.
