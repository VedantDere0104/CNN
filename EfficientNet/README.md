# EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks :- 

Pytorch implementation of EfficientNet . 

## Abstract :- 
Convolutional Neural Networks (ConvNets) are
commonly developed at a fixed resource budget,
and then scaled up for better accuracy if more
resources are available. In this paper, we systematically study model scaling and identify that
carefully balancing network depth, width, and resolution can lead to better performance. Based
on this observation, we propose a new scaling
method that uniformly scales all dimensions of
depth/width/resolution using a simple yet highly
effective compound coefficient. We demonstrate
the effectiveness of this method on scaling up
MobileNets and ResNet.
To go even further, we use neural architecture search to design a new baseline network
and scale it up to obtain a family of models,
called EfficientNets, which achieve much
better accuracy and efficiency than previous
ConvNets. In particular, our EfficientNet-B7
achieves state-of-the-art 84.3% top-1 accuracy
on ImageNet, while being 8.4x smaller and
6.1x faster on inference than the best existing
ConvNet. Our EfficientNets also transfer well and
achieve state-of-the-art accuracy on CIFAR-100
(91.7%), Flowers (98.8%), and 3 other transfer
learning datasets, with an order of magnitude
fewer parameters.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134614874-1009b60e-d414-42a5-8934-f05ffe4147e6.png)

### Model scaling :- 
![image](https://user-images.githubusercontent.com/76057253/134614897-225f363a-488f-4768-a638-a231dc1877fa.png)

### Model Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134616992-3b512de7-be11-46a4-b745-abdde65c09fb.png)


Inverted Res Block and Squeeze Exciatation 



## Results :- 
![image](https://user-images.githubusercontent.com/76057253/134616964-f308aff0-9177-456e-bd9e-72bc31e62ee3.png)
