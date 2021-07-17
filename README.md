# instance-segmentation-mask-rcnn

Instance segmentation with Mask R-CNN

<img src="images/result.png" width="600"/>


## overview

Image segmentation is the task of detecting and distinguishing multiple objects within a single image. There exist two mainstream segmentation paradigms; the **semantic segmentation** in which objects of the same class are assigned the same label, i.e. there is no distinguishing between individual object instances, and **instance segmentation** in which different instances of the same type of object in the input image, for example, car, are assigned distinct labels.

**Mask R-CNN** is an algorithm tailored for instance segmentation.

## repo contents

This repo contains three Google Colab notebooks. 

Two use a pretrained model on the MS COCO dataset - TPU and GPU:

- [mask_rcnn_pretrained_tpu.ipynb](https://github.com/georgiosouzounis/instance-segmentation-mask-rcnn/blob/main/mask-rcnn-pretrained-tpu.ipynb); 
- [mask_rcnn_pretrained_gpu.ipynb](https://github.com/georgiosouzounis/instance-segmentation-mask-rcnn/blob/main/mask_rcnn_pretrained_gpu.ipynb);

And one last one, that trains a custom model using a dataset of oil-stoorage tanks in satellite images, that was originally created for object detection. This nootebook and beyond model training, show-cases how to create simple-shape reference masks and ground-truth annotations, from scratch.

- [mask_rcnn_oiltanks_gpu.ipynb](https://github.com/georgiosouzounis/instance-segmentation-mask-rcnn/blob/main/mask_rcnn_oiltanks_gpu.ipynb); 

## usage

You need a Google account and access to your Google Drive. Copy the contents of this repo and press shift-enter to enjoy the show.


## contact

[Contact the author](mailto:georgios.ouzounis@gmail.com)
