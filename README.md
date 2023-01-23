# TinyMLParking
A TinyML based system to help you find vacant parking spots.

## Model
We use TFLite to train a model on a set of images of individual parking spots, with the labels being "empty" and "occupied". We specifically make use of EfficientNet-Lite, trained on Imagenet (ILSVRC-2012-CLS), optimized for TFLite, designed for performance on mobile CPU, GPU, and EdgeTPU, and finetune it on our custom dataset.

### Examples from dataset:

![Empty](https://github.com/MananSuri27/TinyMLParking/blob/main/TinyMLParking/train_data/test/empty/spot224.jpg)
![Full](https://github.com/MananSuri27/TinyMLParking/blob/main/TinyMLParking/train_data/test/empty/spot224.jpg)
### EfficientNet-Lite
![Model Architecture](https://cdn.discordapp.com/attachments/891317274936483871/1067004937441116160/Z.png)

## System
