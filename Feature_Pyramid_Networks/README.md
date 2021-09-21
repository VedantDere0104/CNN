# Feature Pyramid Networks for Object Detection :- 

## Abstract :- 
Feature pyramids are a basic component in recognition
systems for detecting objects at different scales. But recent
deep learning object detectors have avoided pyramid representations, in part because they are compute and memory
intensive. In this paper, we exploit the inherent multi-scale,
pyramidal hierarchy of deep convolutional networks to construct feature pyramids with marginal extra cost. A topdown architecture with lateral connections is developed for
building high-level semantic feature maps at all scales. This
architecture, called a Feature Pyramid Network (FPN),
shows significant improvement as a generic feature extractor in several applications. Using FPN in a basic Faster
R-CNN system, our method achieves state-of-the-art singlemodel results on the COCO detection benchmark without
bells and whistles, surpassing all existing single-model entries including those from the COCO 2016 challenge winners. In addition, our method can run at 6 FPS on a GPU
and thus is a practical and accurate solution to multi-scale
object detection. 

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134184534-528ed90d-a225-467d-a93e-0e70293fbe71.png)


```
@misc{lin2017feature,
      title={Feature Pyramid Networks for Object Detection}, 
      author={Tsung-Yi Lin and Piotr Dollár and Ross Girshick and Kaiming He and Bharath Hariharan and Serge Belongie},
      year={2017},
      eprint={1612.03144},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
