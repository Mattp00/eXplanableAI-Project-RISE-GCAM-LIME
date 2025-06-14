# eXplanableAI-Project
## This Project aims to analize different eXplanable AI techniques. It can be divided in 3 macro-section.
1) In the first macro-section, different XAI techniques (i.e., RISE, LIME, Grad-CAM, Grad-CAM++) are applied to an image classification task, followed by the extraction of saliency maps using these various methods.
2) In the other section, these techniques are compared using different metrics (Insertion, Deletion, Pointing Game), analyzing their respective advantages and disadvantages.
3) In the last section, an XAI technique is applied in the image classification domain to investigate the presence of biases in the models.

It is important to note that some of the classes and utility functions are derived from the RISE paper (https://arxiv.org/pdf/1806.07421) and its publicly available code on GitHub (https://github.com/eclique/RISE).

## In this project used two different dataset:
1) Imagenet
2) Pascal-VOC-07

This project utilizes a subset of the Imagenet (https://www.kaggle.com/datasets/ambityga/imagenet100) and Pascal-VOC-07 (https://www.kaggle.com/datasets/vijayabhaskar96/pascal-voc-2007-and-2012) public datasets.

To run the pointing game it's necessary to extract the segmentation mask from the pascal voc dataset (I extracted them and they can be found in my public dataset: https://www.kaggle.com/datasets/matteoparrotta/xai-proj-pascal-voc). Otherwise, it's possible to implement the pointing game using the bounding boxes.

The public project can be found directly on kaggle (https://www.kaggle.com/code/matteoparrotta/xai-project-rise-gcam-lime-eval-application)
