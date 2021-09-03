# Path Aggregation Network for Instance Segmentation 

Pytorch implementation of PANNet Paper on top of resnet152
PANNet is very useful architecture for multi scale object detection (used in YOLO v4)

You can easily put the implemented PANNet model on top of any architecture provided 4 stage output (for resnet last 4 Resnet Block output)


Paper :- https://arxiv.org/abs/1803.01534

Abstract  

The way that information propagates in neural networks
is of great importance. In this paper, we propose Path Aggregation Network (PANet) aiming at boosting information
flow in proposal-based instance segmentation framework.
Specifically, we enhance the entire feature hierarchy with
accurate localization signals in lower layers by bottom-up
path augmentation, which shortens the information path between lower layers and topmost feature. We present adaptive feature pooling, which links feature grid and all feature levels to make useful information in each feature level
propagate directly to following proposal subnetworks. A
complementary branch capturing different views for each
proposal is created to further improve mask prediction.
These improvements are simple to implement, with subtle extra computational overhead. Our PANet reaches the
1
st place in the COCO 2017 Challenge Instance Segmentation task and the 2
nd place in Object Detection task without large-batch training. It is also state-of-the-art on MVD
and Cityscapes.

```
@misc{liu2018path,
      title={Path Aggregation Network for Instance Segmentation}, 
      author={Shu Liu and Lu Qi and Haifang Qin and Jianping Shi and Jiaya Jia},
      year={2018},
      eprint={1803.01534},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
