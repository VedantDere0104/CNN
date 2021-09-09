# CSPNET: A NEW BACKBONE THAT CAN ENHANCE LEARNING CAPABILITY OF CNN

Implementation of CSPDenseNet in pytorch from scratch . 
CSP DenseNet is used as a backbone in objection detection (YOLO v4) . It is based on DenseNet architecture but in more efficient manner .


## DenseNet and CSPDenseNet
![CSPNet](https://user-images.githubusercontent.com/76057253/132621011-618620b1-7190-4c2b-b848-aa8fe0b5a031.png)

To increase efficiency they spilit in_channels of image in two parts and then passed through DenseNet layers and before transition layer the are concating the split part with the output of DenseNet Layer

## Abstract :- 
Neural networks have enabled state-of-the-art approaches to achieve incredible results on computer
vision tasks such as object detection. However, such success greatly relies on costly computation
resources, which hinders people with cheap devices from appreciating the advanced technology. In
this paper, we propose Cross Stage Partial Network (CSPNet) to mitigate the problem that previous
works require heavy inference computations from the network architecture perspective. We attribute
the problem to the duplicate gradient information within network optimization. The proposed
networks respect the variability of the gradients by integrating feature maps from the beginning and
the end of a network stage, which, in our experiments, reduces computations by 20% with equivalent
or even superior accuracy on the ImageNet dataset, and significantly outperforms state-of-the-art
approaches in terms of AP50 on the MS COCO object detection dataset. The CSPNet is easy to
implement and general enough to cope with architectures based on ResNet, ResNeXt, and DenseNet.

```
@misc{wang2019cspnet,
      title={CSPNet: A New Backbone that can Enhance Learning Capability of CNN}, 
      author={Chien-Yao Wang and Hong-Yuan Mark Liao and I-Hau Yeh and Yueh-Hua Wu and Ping-Yang Chen and Jun-Wei Hsieh},
      year={2019},
      eprint={1911.11929},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
