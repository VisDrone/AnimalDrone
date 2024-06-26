# AnimalDrone
![VisDrone](https://github.com/VisDrone/AnimalDrone/blob/master/data_collection.jpg)


## Introduction

We propose a large-scale video based animal counting dataset collected by drones (AnimalDrone) for agriculture and wildlife protection. The dataset consists of two subsets, i.e., AnimalDrone-PartA that are captured on site by our own drones and AnimalDrone-PartB that are collected from Internet. Totally, there are 53,644 frames with more than 4 million object annotations and several attributes, i.e., density, altitude and view. Moreover, we develop a graph regularized flow attention network (GFAN) to perform density map estimation in dense crowds of video clips captured by drones with arbitrary crowd density, perspective, and flight altitude. Specifically, our GFAN method uses optical flow to warp the multi-scale feature maps in sequential frames to guarantee the temporal coherency, and then combines the enhanced features to predict the density maps. Besides, a graph regularizer is imposed on the density maps of multiple neighborhood frames to further enhance temporal relations. We develop a new multi-granularity loss function including pixel-wise density loss and region-wise count loss to enforce the network to concentrate on discriminative features for different scales of objects in various scenes with different density. A detailed quantitative study is performed and compared with recent state-of-the-art counting algorithms, which demonstrates the effectiveness of the proposed method.

![VisDrone](https://github.com/VisDrone/AnimalDrone/blob/master/dataset.jpg)

## Dataset

Baidu:

[AnimalDrone-PartA](https://pan.baidu.com/s/16Yh3ylOfuvWGEpkLHXksnQ?pwd=1895)

Extraction code：1895

[AnimalDrone-PartB](https://pan.baidu.com/s/1lBQFzt5dk8_6XnCDWNnlzw?pwd=1895)  

Extraction code：1895

Google:  

AnimalDrone-PartA 

AnimalDrone-PartB

## GFAN


## Citation

```bibtex
@article{zhu2021graph,
  title={Graph Regularized Flow Attention Network for Video Animal Counting from Drones},
  author={Zhu, Pengfei and Peng, Tao and Du, Dawei and Yu, Hongtao and Zhang, Libo and Hu, Qinghua},
  journal={IEEE Transactions on Image Processing},
  year={2021},
  publisher={IEEE}
}
```

