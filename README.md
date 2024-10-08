[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/geonda/CGCNN_tutorial_lecture7.git/HEAD)

## The hands-on part for the lecture 7 of intro to materials informatics. 
---

This CGCNN tutorial is a modified version of the original tutorial available [here](https://github.com/Diego-2504/CGCNN_tutorial). It is primarily based on the research conducted by T. Xie and J. Grossman. Original implementaioncan be found [here](https://github.com/txie-93/cgcnn) and detailed in the paper titled ["Crystal Graph Convolutional Neural Networks for an Accurate and Interpretable Prediction of Material Properties"](https://arxiv.org/abs/1710.10324).

### 1. Crystal_graphs
This jupyter notebook includes most of the scripts that come in the repository, that's why I divided it into 3 parts:

> #### 1.1 Data analysis
> In this part of the notebook I explain the way they read the cif files from the crystals.
> Afterwards I give an exhaustive explanation of the construction of graphs from the crystal.

> #### 1.2 Batches
> In this part of the notebook I explain how to create the batches that 
> will be passed as input to the model.

> #### 1.3 Model
> In this part of the notebook I describe the convolutions in the graphs and then the model in general.
> Finally I perform a small training of material classification (whether it is metal or semiconductor) to test the model.

