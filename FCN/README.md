# Fully Convolutional Networks for Semantic Segmentation :-

## Abstract :- 
Convolutional networks are powerful visual models that
yield hierarchies of features. We show that convolutional networks by themselves, trained end-to-end, pixelsto-pixels, exceed the state-of-the-art in semantic segmentation. Our key insight is to build “fully convolutional”
networks that take input of arbitrary size and produce
correspondingly-sized output with efficient inference and
learning. We define and detail the space of fully convolutional networks, explain their application to spatially dense
prediction tasks, and draw connections to prior models. We
adapt contemporary classification networks (AlexNet [19],
the VGG net [31], and GoogLeNet [32]) into fully convolutional networks and transfer their learned representations
by fine-tuning [4] to the segmentation task. We then define a novel architecture that combines semantic information from a deep, coarse layer with appearance information
from a shallow, fine layer to produce accurate and detailed
segmentations. Our fully convolutional network achieves
state-of-the-art segmentation of PASCAL VOC (20% relative improvement to 62.2% mean IU on 2012), NYUDv2,
and SIFT Flow, while inference takes less than one fifth of a
second for a typical image.


## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134184140-21dd1795-56dd-4ad4-9b49-ab656b7d2d20.png)

## Results :- 
![image](https://user-images.githubusercontent.com/76057253/134184239-da22fdab-c5a1-40bf-8c08-17398c905036.png)


```
@misc{long2015fully,
      title={Fully Convolutional Networks for Semantic Segmentation}, 
      author={Jonathan Long and Evan Shelhamer and Trevor Darrell},
      year={2015},
      eprint={1411.4038},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
