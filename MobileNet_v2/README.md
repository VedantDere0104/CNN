# MobileNetV2: Inverted Residuals and Linear Bottlenecks :- 

Pytorch implementation of MobileNet v2

## Abstract :- 
In this paper we describe a new mobile architecture,
MobileNetV2, that improves the state of the art performance of mobile models on multiple tasks and benchmarks as well as across a spectrum of different model
sizes. We also describe efficient ways of applying these
mobile models to object detection in a novel framework
we call SSDLite. Additionally, we demonstrate how
to build mobile semantic segmentation models through
a reduced form of DeepLabv3 which we call Mobile
DeepLabv3.
is based on an inverted residual structure where
the shortcut connections are between the thin bottleneck layers. The intermediate expansion layer uses
lightweight depthwise convolutions to filter features as
a source of non-linearity. Additionally, we find that it is
important to remove non-linearities in the narrow layers
in order to maintain representational power. We demonstrate that this improves performance and provide an intuition that led to this design.
Finally, our approach allows decoupling of the input/output domains from the expressiveness of the transformation, which provides a convenient framework for
further analysis. We measure our performance on
ImageNet  classification, COCO object detection ,
VOC image segmentation . We evaluate the trade-offs
between accuracy, and number of operations measured
by multiply-adds (MAdd), as well as actual latency, and
the number of parameters.


## Architecture :- 

![image](https://user-images.githubusercontent.com/76057253/134532895-a30796e3-51b7-4ab0-9749-a9c42ff34b92.png)

## Residual Block and Inverted Residual Block :- 
![image](https://user-images.githubusercontent.com/76057253/134533059-116f371c-0f34-4b05-9a0d-cc7b2ac7911b.png)


```
@misc{sandler2019mobilenetv2,
      title={MobileNetV2: Inverted Residuals and Linear Bottlenecks}, 
      author={Mark Sandler and Andrew Howard and Menglong Zhu and Andrey Zhmoginov and Liang-Chieh Chen},
      year={2019},
      eprint={1801.04381},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
