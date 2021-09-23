# MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications


Pytorch implementation of MobileNet v1 

## Abstract :- 
We present a class of efficient models called MobileNets
for mobile and embedded vision applications. MobileNets
are based on a streamlined architecture that uses depthwise separable convolutions to build light weight deep
neural networks. We introduce two simple global hyperparameters that efficiently trade off between latency and
accuracy. These hyper-parameters allow the model builder
to choose the right sized model for their application based
on the constraints of the problem. We present extensive
experiments on resource and accuracy tradeoffs and show
strong performance compared to other popular models on
ImageNet classification. We then demonstrate the effectiveness of MobileNets across a wide range of applications and
use cases including object detection, finegrain classification, face attributes and large scale geo-localization.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134519747-dfe1011f-3e90-4884-a011-e37a58e29115.png)

## Results :- 
We get mobile or edge device scalable model with width multiplier and resolution multiplier .


![2021-09-23](https://user-images.githubusercontent.com/76057253/134520386-c29e1efa-5d2e-4049-9e6b-5b05054b5854.png)

```
@misc{howard2017mobilenets,
      title={MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications}, 
      author={Andrew G. Howard and Menglong Zhu and Bo Chen and Dmitry Kalenichenko and Weijun Wang and Tobias Weyand and Marco Andreetto and Hartwig Adam},
      year={2017},
      eprint={1704.04861},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
