# RegNet
Implementation of RegNet which builds on ResNet by adding an RNN-Regulator Module to preserve the spatio-temporal data between residual blocks.
No official code of the [RegNet]( https://arxiv.org/abs/2101.00590) paper was provided so I created this repository. Read the paper at https://arxiv.org/abs/2101.00590 . Pull requests
are most certainly welcome :)

# Get Started

[Install the required laibraries and packages]

pip install torchmetrics

pip install pytorch_lightning

pip install tune

pip install ray[tune]

# Run 
python regnet.py --tune
