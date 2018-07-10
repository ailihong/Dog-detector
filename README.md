# Dog-detector
Python script to detect dog(s) in an image

MobileNet architecture and the Single Shot Detector (SSD) framework are used for detecting dogs in an image.
The model we’ll be using in this blog post is a Caffe version of the original TensorFlow implementation by Howard et al. and was trained by chuanqi305 (https://github.com/chuanqi305/MobileNet-SSD).
The MobileNet SSD was first trained on the COCO dataset (Common Objects in Context) and was then fine-tuned on PASCAL VOC.
