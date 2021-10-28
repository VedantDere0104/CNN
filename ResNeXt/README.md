# Aggregated Residual Transformations for Deep Neural Networks :- 

Pytorch implementation of ResNeXt .


## Abstract :- 
We present a simple, highly modularized network architecture for image classification. Our network is constructed
by repeating a building block that aggregates a set of transformations with the same topology. Our simple design results in a homogeneous, multi-branch architecture that has
only a few hyper-parameters to set. This strategy exposes a
new dimension, which we call “cardinality” (the size of the
set of transformations), as an essential factor in addition to
the dimensions of depth and width. On the ImageNet-1K
dataset, we empirically show that even under the restricted
condition of maintaining complexity, increasing cardinality
is able to improve classification accuracy. Moreover, increasing cardinality is more effective than going deeper or
wider when we increase the capacity. Our models, named
ResNeXt, are the foundations of our entry to the ILSVRC
2016 classification task in which we secured 2nd place.
We further investigate ResNeXt on an ImageNet-5K set and
the COCO detection set, also showing better results than
its ResNet counterpart.

## Architecture :- 

![image](https://user-images.githubusercontent.com/76057253/139263808-4f2d7f77-0225-48de-abce-af5e807e2a97.png)

![image](https://user-images.githubusercontent.com/76057253/139263845-cdc7b767-777d-4ee4-97bd-d72543767a49.png)

## Results :- 
![image](https://user-images.githubusercontent.com/76057253/139263923-768a2240-2ad6-4fdc-a33d-cd4ef3edb4f4.png)



```
@misc{xie2017aggregated,
      title={Aggregated Residual Transformations for Deep Neural Networks}, 
      author={Saining Xie and Ross Girshick and Piotr Dollár and Zhuowen Tu and Kaiming He},
      year={2017},
      eprint={1611.05431},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

```
