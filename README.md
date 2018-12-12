# Spherical Superpixel
This repository contains the dataset, the evaluation code and the source code of our works on spherical superpixels.

## Dataset
Currently, our dataset contains 75 manually annotated spherical panoramas. The original panoramas are selected from [SUN360](https://vision.princeton.edu/projects/2012/SUN360/data/) dataset. Each image is resized to 1024x512 pixels and segmented with an annotation tool based on the application provided by the authors of [BSD](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/) dataset.

For each spherical panorama, we provide the ground truth segmentations and ground truth boundaries. Some annotation examples are shown below. 
![image](./Figs/dataset.png)
Our dataset can be downloaded at [SPSDataset75](http://scs.tju.edu.cn/~lwan/data/spsdataset/spsdataset75.rar). If you use this dataset in published work, please cite our paper as
```
@InProceedings{SPSDataset75,
    author     = {Liang Wan and Xiaorui Xu and Qiang Zhao and Wei Feng},
    title      = {Spherical Superpixels: Benchmark and Evaluation},
    booktitle  = {ACCV},
    YEAR       = {2018},
}
```

## Code
Evaluation code and source code will be released in the future.
