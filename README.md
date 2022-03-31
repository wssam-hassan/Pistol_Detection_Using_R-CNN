# Pistol_Detection_Using_R-CNN

## About The Project
This project is a part of the pipeline of the final project [Weapon Detection System](https://github.com/wssam-hassan/YoloV4-Weapons-Detection)<br>
As the first and supreme goal of science is to serve man-kind, and since the security and safety is one of the first and most important priorities, we worked on “Weapon Dectection Sysyem” depending on artificial intelligence and deep learning technologies that can detect weapons such as: pistols, knifes and rifles.<br>
Starting with training several models including Region-Based Convolutional Neural Network (R-CNN), especially Faster R-CNN, with only pistols dataset to measure its performance.

## Dataset
[Pistol Detection Dataset](https://github.com/ari-dasci/OD-WeaponDetection/tree/master/Pistol%20detection)<br>
Provided by [Andalusian Research Institute in Data Science and Computational Intelligence](https://dasci.es/)<br>
licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)

## Getting Started
The project is totally run on google colab, you can run the [notebook](Pistol_Detection_Using_Faster_R_CNN.ipynb) on colab,
put [generate_tfrecord.py script](generate_tfrecord.py) inside the project directory and [configuration file](faster_rcnn_resnet50_v1_640x640_coco17_tpu-8.config) inside data folder.
Otherwise replace the paths of those files inside code to your desired path you put files in.

## Results
After 34K training step, the model gives these results:

|   Total Loss  |   Precision   |     Recall    |     F1-Score  |     mAP@0.5 |
| ------------- | ------------- | ------------- | ------------- | ----------- |
|   0.051       |    0.72       |     0.78      |     0.748     |   0.869     |

## Test On Images
<img src="https://user-images.githubusercontent.com/86083432/160951464-9d312ec7-f823-49e1-b1af-f2ee8cf0595d.png" width="500" height="380"><img src="https://user-images.githubusercontent.com/86083432/160951545-267f119d-f872-488c-bc0c-8ece62b86b3b.png" width="500" height="380">
<br>
<img src="https://user-images.githubusercontent.com/86083432/160951491-13f33a8b-9f34-4c46-aa28-712d612a4792.png" width="500" height="371"><img src="https://user-images.githubusercontent.com/86083432/160951510-2312b35d-e88c-4d51-ad27-d31ac152ea8c.png" width="500">

## Test On Video
https://user-images.githubusercontent.com/86083432/151704437-b24bbfda-a267-41c5-9705-1ecc334725e1.mp4
