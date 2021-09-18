# CBAM: Convolutional Block Attention Module :- 

Pytorch implementation of CBAM with ResNet .

## Abstract :- 
We propose Convolutional Block Attention Module (CBAM),
a simple yet effective attention module for feed-forward convolutional
neural networks. Given an intermediate feature map, our module sequentially infers attention maps along two separate dimensions, channel
and spatial, then the attention maps are multiplied to the input feature
map for adaptive feature refinement. Because CBAM is a lightweight and
general module, it can be integrated into any CNN architectures seamlessly with negligible overheads and is end-to-end trainable along with
base CNNs. We validate our CBAM through extensive experiments on
ImageNet-1K, MS COCO detection, and VOC 2007 detection datasets.
Our experiments show consistent improvements in classification and detection performances with various models, demonstrating the wide applicability of CBAM. The code and models will be publicly available.

# Architecture :- 

![2021-09-18](https://user-images.githubusercontent.com/76057253/133873671-eb648dae-16bc-40ed-95c9-0569f16ffcfb.png)

### Channel Attention Module and Sparse Attention Module :-
![2021-09-18 (1)](https://user-images.githubusercontent.com/76057253/133873691-9dcd0935-3633-4cbb-8fcf-50c3f84c3a03.png)

### Convolutional Block Attention Module with Resnet :- 
![2021-09-18](https://user-images.githubusercontent.com/76057253/133873711-4713ef21-b2fe-481a-8379-4a4a2f45bc2e.png)


```
@misc{woo2018cbam,
      title={CBAM: Convolutional Block Attention Module}, 
      author={Sanghyun Woo and Jongchan Park and Joon-Young Lee and In So Kweon},
      year={2018},
      eprint={1807.06521},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
