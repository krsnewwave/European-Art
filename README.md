# Overview

This repository contains notebooks to train Pytorch models. This is for research purposes only.

The notebooks can be consumed in order:
1. `display-european-art` - just EDA
1. `model-european-art` - comparing ResNet18, 34 and 50, with the feature extractor layers frozen.
1. `model-european-art-resnet-18` - using ResNet18, with the top using `model-european-art` and all layers unfrozen.
1. `visualize-european-art-resnet-18` - visualizing `model-european-art-resnet-18` using this [repository](https://github.com/utkuozbulak/pytorch-cnn-visualizations).
1. `model-european-art-resnet-18-multilabel` - trying out multi-task learning.

This code uses the [Historic Art Dataset](https://www.kaggle.com/datasets/ansonnnnn/historic-art) from Kaggle. From its description:

> European artworks from the 3rd to 19th century, gathered from the Web Gallery of Art. (https://www.wga.hu). <br>...<br> The directory contains (I) all the images retrieved from the website using a web scraping script, (II) a dataset detailing all the artists background, such as time period and nationality, and (III) a dataset detailing all the images information along with their corresponding IDs.

