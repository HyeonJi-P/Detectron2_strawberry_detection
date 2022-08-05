# Detectron2_strawberry_detection
Detectron2를 이용한 Strawberry flower object detection

# Detectron2 Repo
[Detecton2](https://github.com/facebookresearch/detectron2)
 
# Material & Method
<h3> Data </h3>

* **Total 1954 images** (Strawberry Closeup)
* **1666** for Train, **95** for Validation, **193** for Test(Evaluation)
* Annotation : Strawberry Flower (Bounding Box)
<h3> Train </h3>

* **Faster R-CNN R50 FPN 3x** pre-trained model used(ImageNet)
* Epoch = ( batch_size * Iter )/ Total number of Images 
* **Validation loss process added**
* **Custom Data Loader** 
