# zero2dcnn
Incrementally building up to modern multilabel classification.
Resources
* [fastbook](https://github.com/fastai/fastbook), for deeper explanations of each topic.
* [Think Python](https://greenteapress.com/wp/think-python/) for foundational knowledge about programming and python

# Contents
1. [Linear layers](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/1_linear.ipynb)
1. [MNIST Binary Classifier](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/2_mnist_binary.ipynb)
1. [MNIST Multiclass Classifier](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/3a_fashionmnist_multiclass.ipynb)
1. [CIFAR10 Multiclass Classifier](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/3b_cifar10_multiclass.ipynb)
1. [Improving CIFAR10 Accuracy](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/4_improving_cifar10.ipynb)
1. [Resnet](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/5_resnet.ipynb)
1. [Foreground Segmentation](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/6_segmentation.ipynb)
1. [U-NET](https://colab.research.google.com/github/kyflores/zero2dcnn/blob/main/7_unet.ipynb)

# Setup
### Colab
All the necessary packages except torchinfo should be preinstalled.
Just open a cell and run `!pip install torchinfo` if the notebook doesn't install it automatically.

### Conda
You can install everything locally with `conda` or any of its clones.
1. `conda create -n cnn python=3.10 pip pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia`
1. `conda activate cnn`
1. `pip install jupyterlab ipywidgets torchinfo tqdm matplotlib`

And then start Jupyter like this
1. `conda activate cnn`
1. `jupyter lab`
