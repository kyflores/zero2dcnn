# roadtodcnn
Incrementally building up to modern multilabel classification.

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