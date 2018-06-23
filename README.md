# A loss function (Weighted Hausdorff Distance)  <br>for object localization

  This repository contains the PyTorch implementation of the Weighted Hausdorff Loss described in this paper:
  [Weighted Hausdorff Distance: A Loss Function For Object Localization](https://arxiv.org/abs/1806.07564)

![Some object centers](https://raw.githubusercontent.com/javiribera/weighted-hausdorff-loss/master/fig/dots.png)
  
  ## Abstract
  Recent advances in Convolutional Neural Networks (CNN) have achieved remarkable results in localizing objects in images. In these networks, the training procedure usually requires providing bounding boxes or the maximum number of expected objects. In this paper, we address the task of estimating object locations without annotated bounding boxes, which are typically hand-drawn and time consuming to label. We propose a loss function that can be used in any Fully Convolutional Network (FCN) to estimate object locations. This loss function is a modification of the Average Hausdorff Distance between two unordered sets of points. The proposed method does not require one to "guess" the maximum number of objects in the image, and has no notion of bounding boxes, region proposals, or sliding windows. We evaluate our method with three datasets designed to locate people's heads, pupil centers and plant centers. We report an average precision and recall of 94% for the three datasets, and an average location error of 6 pixels in 256x256 images. 
  
  ## Citation
  J. Ribera, D. G&uuml;era, Y. Chen, E. Delp, "Weighted Hausdorff Distance: A Loss Function For Object Localization", arXiv preprint [arXiv:1806.07564](https://arxiv.org/abs/1806.07564), June 2018
  
```
@article{whd-loss,
  title={Weighted Hausdorff Distance: A Loss Function For Object Localization},
  author={J. Ribera and D. G{\"u}era and Y. Chen and E. Delp},
  journal={arXiv:1806.07564},
  month={June},
  year={2018}
}
```

  ## Datasets
  The datasets used in the paper can be downloaded from these links:
  - [Mall dataset](http://personal.ie.cuhk.edu.hk/~ccloy/downloads_mall_dataset.html)
  - [Pupil dataset](http://www.ti.uni-tuebingen.de/Pupil-detection.1827.0.html)
  - [Plant dataset](https://engineering.purdue.edu/~sorghum/dataset-plant-centers-2016)

  ## Code
  To be uploaded soon.
