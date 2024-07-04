# Drone Build YOLO V8

Training and validation with yolov8 with the [builddetect](https://universe.roboflow.com/arturwork/builddetect/dataset/5) dataset (segmented labeling) where training is carried out normally and transfer learning

It is concluded that training with transfer learning, specifically with "coco", gives better performance.


----
# Segmentation
## Normal way

Validation
<p align="center">
  <img src="README-images/segmentationvalidationNormal.png" alt="Step1">
</p>

ConfusionMatrix Training
<p align="center">
  <img src="README-images/segmentationconfusion_matrixNormal.png" alt="Step1">
</p>

Results YOLO V8  Training
<p align="center">
  <img src="README-images/segmenationresultsNormal.png" alt="Step1">
</p>

----

## Transfer Learning  way

Validation
<p align="center">
  <img src="README-images/SegmentationvalidationTransfer.png" alt="Step1">
</p>

ConfusionMatrix Training
<p align="center">
  <img src="README-images/segmentationconfusion_matrixTransfer.png" alt="Step1">
</p>

Results YOLO V8  Training
<p align="center">
  <img src="README-images/segmentationresultsTransfer.png" alt="Step1">
</p>



----
# Detection
## Normal way

Validation
<p align="center">
  <img src="README-images/normalvalidation.png" alt="Step1">
</p>

ConfusionMatrix Training
<p align="center">
  <img src="README-images/confusion_matrixNormaltraining.png" alt="Step1">
</p>

Results YOLO V8  Training
<p align="center">
  <img src="README-images/resultstrainNormal.png" alt="Step1">
</p>

----

## Transfer Learning  way

Validation
<p align="center">
  <img src="README-images/transfervalidation.png" alt="Step1">
</p>

ConfusionMatrix Training
<p align="center">
  <img src="README-images/confusion_matrixtrainTransfer.png" alt="Step1">
</p>

Results YOLO V8  Training
<p align="center">
  <img src="README-images/resultsTransfer.png" alt="Step1">
</p>


