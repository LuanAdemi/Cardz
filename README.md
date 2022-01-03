# Cardz
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
<a href="https://www.kaggle.com/luanademi/playing-card-ensemble-segmentation-masks"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a>
[![forthebadge](https://forthebadge.com/images/badges/works-on-my-machine.svg)](https://forthebadge.com)

Cardz is my take on playing card localization and classification in a scence with multiple cards.

<img src="https://i.ibb.co/BTPTLS5/Cardz.png" alt="Cardz" border="0">

# Model
The model consists of an UNet trained with random card ensembles and their segmentation masks. The trained models can be found in results.

# Files
This repository contains a notebook explaining the biggest model and analysing its perfomance using <a href="https://captum.ai/">Captum</a>.

Here is a basic table of contents:

- Classifier: Training the model
- Captum: Evaluating the model quality using Captum

# Dataset
<img src="https://i.ibb.co/9VbcpJH/Cardz-Data.png" alt="Cardz-Data" border="0">
The dataset was generated using several decks of cards and the <a href="https://www.robots.ox.ac.uk/~vgg/data/dtd/">DTD dataset</a>. 
<a href="https://github.com/Davanchama">@Davanchama</a> (thank you very much) and I made photos of these decks and wrote a script to genrate the dataset.
You can find the dataset on <a href="https://www.kaggle.com/luanademi/playing-card-ensemble-segmentation-masks">kaggle</a>. 


# References
- [1] **U-Net: Convolutional Networks for Biomedical Image Segmentation**, *Olaf Ronneberger, Philipp Fischer, Thomas Brox*  
[![arXiv](https://img.shields.io/badge/arXiv-1505.04597-b31b1b.svg)](https://arxiv.org/abs/1505.04597)
- [2] **Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization**, *Ramprasaath R. Selvaraju, Michael Cogswell, et al.*
[![arXiv](https://img.shields.io/badge/arXiv-1610.02391-b31b1b.svg)](https://arxiv.org/abs/1610.02391)

# Techstack
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

