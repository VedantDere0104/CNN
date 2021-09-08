# Densely Connected Convolutional Networks :- 

DenseNet implementation in pytorch from scratch . 
DenseNet is very useful architecture as a Backbone in Object Detection and also CSPNet is based on DenseNet .

## Abstract :- 

Recent work has shown that convolutional networks can
be substantially deeper, more accurate, and efficient to train
if they contain shorter connections between layers close to
the input and those close to the output. In this paper, we
embrace this observation and introduce the Dense Convolutional Network (DenseNet), which connects each layer
to every other layer in a feed-forward fashion. Whereas
traditional convolutional networks with L layers have L
connections—one between each layer and its subsequent
layer—our network has L(L+1)/2
direct connections. For
each layer, the feature-maps of all preceding layers are
used as inputs, and its own feature-maps are used as inputs
into all subsequent layers. DenseNets have several compelling advantages: they alleviate the vanishing-gradient
problem, strengthen feature propagation, encourage feature reuse, and substantially reduce the number of parameters. We evaluate our proposed architecture on four highly
competitive object recognition benchmark tasks (CIFAR-10,
CIFAR-100, SVHN, and ImageNet). DenseNets obtain significant improvements over the state-of-the-art on most of
them, whilst requiring less computation to achieve high performance.


```
@misc{huang2018densely,
      title={Densely Connected Convolutional Networks}, 
      author={Gao Huang and Zhuang Liu and Laurens van der Maaten and Kilian Q. Weinberger},
      year={2018},
      eprint={1608.06993},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

```
