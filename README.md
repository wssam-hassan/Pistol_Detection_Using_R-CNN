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
<img src="https://drive.google.com/uc?export=view&id=1V9DxyoD6rKbjU4Ar_V2b4EglWn0FqwNA" width="500" height="380"><img src="https://drive.google.com/uc?export=view&id=1gmd4jrxluWBKo8uc7zP_A9PTVb82ae4i" width="500" height="380">
<br>
<img src="https://drive.google.com/uc?export=view&id=1927jkrbfAs5rUh24gbbSNvIhjhTalILw" width="500" height="371"><img src="https://drive.google.com/uc?export=view&id=1u8fWBcIRBxM0huwTqlculgcx1PRjWu_S" width="500">

## Test On Video
https://user-images.githubusercontent.com/86083432/151704437-b24bbfda-a267-41c5-9705-1ecc334725e1.mp4
