# Body-Shape-Classification
**Deep Learning Empowering Women's Fashion with Grounded-Segment-Anything Segmentation for Body Shape Classification**

This repository provides a PyTorch implementation for classifying body shapes using image segmentation. The goal of this study is to classify body shapes into five categories: Rectangle, Triangle, Inverted Triangle, Hourglass, and Apple, using the Style4BodyShape dataset. for this purpose body shape segmentation masks were extracted. By leveraging the body shape segmentation masks, the model focuses solely on the body shape information while disregarding the surroundings and background. 

**Dataset**

The Style4BodyShape dataset is utilized in this project. It consists of images of 270 women in various outfits. The outfits are categorized into five main classes: dresses, pants, skirts, tops, and outerwear. To clean the dataset, only images in which the subject is wearing form-fitting clothing and their hands are separated from their bodies are retained.

**Models**

Various pre-trained models are employed for the classification of the body shape segmentation results. The following models have been utilized:

ResNet18

ResNet34

ResNet50

VGG16

VGG19

Inception v3

