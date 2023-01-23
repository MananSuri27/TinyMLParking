# TinyMLParking
A TinyML based system to help you find vacant parking spots.

## Model
We use TFLite to train a model on a set of images of individual parking spots, with the labels being "empty" and "occupied". We specifically make use of EfficientNet-Lite, trained on Imagenet (ILSVRC-2012-CLS), optimized for TFLite, designed for performance on mobile CPU, GPU, and EdgeTPU, and finetune it on our custom dataset.

### Examples from dataset:
### EfficientNet-Lite
![Model Architecture](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.researchgate.net%2Ffigure%2FThe-network-architecture-of-EfficientNet-It-can-output-a-feature-map-with-deep-semantic_fig3_349299852&psig=AOvVaw3P7xn-7wuIgI8sV-gAlqXC&ust=1674550448575000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCMi46tao3fwCFQAAAAAdAAAAABAE)

## System
