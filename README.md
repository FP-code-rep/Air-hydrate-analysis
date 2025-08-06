# Air-hydrate-analysis
#### This repository presents scripts (jupyter notebooks) used for the image segmentation of air hydrate inclusions from microphotographs of polar ice.


## Contents
- The "segmentation_and_filtering" folder contains two separate jupyter notebooks for the "segmentation" and "filtering" step. The .png files summarize the respective image processing routines.
- The "ground_truth" folder contains a jupyter notebook and an example folder to run the code.


## Running the code
To run the code, execute the individual code cells.
<br>
For "segmentation_and_filtering", the segmentation step has to be performed before the filtering step. The segmentation notebook generates the directories and files necessary for the the filtering notebook.
<br>
In the segmentation notebook, "set paths and name" and "Segmentation parameters" should be changed accordingly.
<br>
In the filtering notebook, "set paths and name" and main- as well as specific filtering variables should be changed accordingly.


## Python environment and package versions
#### The scripts were developed using an anaconda environment with Python 3.10.13
The following packages were used:
- Jupyter notebook (7.2.2)
- OpenCV (4.10.0)
- Scikit-image (0.24.0)
- Scikit-learn (1.5.2)
- Numpy (2.1.3)
- Scipy (1.14.1)
- Pandas (2.2.3)
- Matplotlib (3.9.3)
- sys
- os
- glob
- time
- pathlib
