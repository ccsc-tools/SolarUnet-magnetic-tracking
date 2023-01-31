## Identifying and Tracking Solar Magnetic Flux Elements with Deep Learning
[![DOI](https://github.com/ccsc-tools/zenodo_icons/blob/main/icons/solarunet.svg)](https://zenodo.org/badge/latestdoi/416091196)

## Authors

Haodi Jiang, Jiasheng Wang, Chang Liu, Ju Jing, Hao Liu, Jason T. L. Wang and Haimin Wang

## Contributor
Yasser Abduallah


## Abstract

Deep learning has drawn significant interest in recent years due to its effectiveness in processing 
big and complex observational data gathered from diverse instruments. 
Here we propose a new deep learning method, called SolarUnet, 
to identify and track solar magnetic flux elements or features in observed vector
magnetograms based on the Southwest Automatic Magnetic Identification Suite (SWAMIS).
Our method consists of a data pre-processing component that prepares 
training data from the SWAMIS tool, a deep learning model implemented 
as a U-shaped convolutional neural network for fast and accurate image segmentation, 
and a post-processing component that prepares tracking results. 
SolarUnet is applied to data from the 1.6 meter Goode Solar 
Telescope at the Big Bear Solar Observatory. 
When compared to the widely used SWAMIS tool, 
SolarUnet is faster while agreeing mostly with SWAMIS on feature size and flux distributions, 
and complementing SWAMIS in tracking long-lifetime features. 
Thus, the proposed physics-guided deep learning-based tool 
can be considered as an alternative method for solar magnetic tracking.

## Binder

This notebook is Binder enabled and can be run on [mybinder.org](https://mybinder.org/) by using the link below.


### run_SolarUnet.ipynb (Jupyter Notebook for SolarUnet)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ccsc-tools/SolarUnet-magnetic-tracking/HEAD?labpath=run_SolarUnet.ipynb) 

Please note that starting Binder might take some time to create and start the image.

For the latest updates of SolarUnet refer to [https://github.com/deepsuncode/SolarUnet-magnetic-tracking](https://github.com/deepsuncode/SolarUnet-magnetic-tracking)

## Installation on local machine
Note: Tested on Python version 3.9.13
|Library | Version   | Description  |
|---|---|---|
|astropy|5.1  |Astronomy and astrophysics data processing|
|cv2| 4.7.0   | Image processing|
| keras  | 2.11.0  |Artificial neural networks API   |
|matplotlib|3.5.2| Plotting and graphs|
|numpy| 1.21.5| Array manipulation|
|scikit-image| 0.19.2| Image processing|
|scikit-learn| 1.0.2 | Machine learning|
| scipy  | 1.9.1  |Science and math   |
| tensorflow  | 2.11.0 | Neural network libraries  |

## References
Identifying and Tracking Solar Magnetic Flux Elements with Deep Learning. H. Jiang, J. Wang, C. Liu, J. Jing, H. Liu, J. T. L. Wang, H. Wang, ApJS, 250:5, 2020.

https://iopscience.iop.org/article/10.3847/1538-4365/aba4aa

http://arxiv.org/abs/2008.12080

https://web.njit.edu/~wangj/SolarUnet/
