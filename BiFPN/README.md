# Bi-directional Feature Pyramid Network :- 
Pytorch implementation of BiFPN layer on top of Resnet Backbone .

## Abstract :- 
Model efficiency has become increasingly important in
computer vision. In this paper, we systematically study neural network architecture design choices for object detection
and propose several key optimizations to improve efficiency.
First, we propose a weighted bi-directional feature pyramid network (BiFPN), which allows easy and fast multiscale feature fusion; Second, we propose a compound scaling method that uniformly scales the resolution, depth, and
width for all backbone, feature network, and box/class prediction networks at the same time. Based on these optimizations and better backbones, we have developed a new family
of object detectors, called EfficientDet, which consistently
achieve much better efficiency than prior art across a wide
spectrum of resource constraints. In particular, with singlemodel and single-scale, our EfficientDet-D7 achieves stateof-the-art 55.1 AP on COCO test-dev with 77M parameters and 410B FLOPs1
, being 4x – 9x smaller and using
13x – 42x fewer FLOPs than previous detectors.

## Architecture :- 
BiFPN architecture with backbone EfficientNet Model but instead of EfficientNet model I am using Resnet for simplicity . 
 
 ![image](https://user-images.githubusercontent.com/76057253/134845147-3663f702-bca9-46b1-9969-b48c72589df2.png)
 
 ### Different Types of Feature Pyramid Networks :- 
 
 ![image](https://user-images.githubusercontent.com/76057253/134845239-5252e0ca-2fd5-414d-9505-c939768c4c19.png)

```
@misc{tan2020efficientdet,
      title={EfficientDet: Scalable and Efficient Object Detection}, 
      author={Mingxing Tan and Ruoming Pang and Quoc V. Le},
      year={2020},
      eprint={1911.09070},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
