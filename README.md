# HydraNets-for-Multitask-Learning
This repository contains the Jupyter Notebooks for HydraNets for multi-task learning for machine learning and and computer vision tasks. These tasks are :

#### *Machine Learning*
* Classification
* Regression

#### *Computer Vision*
* Image Segmentation
* Depth Map


The machine learning tasks are performed on the **UTKFace** dataset while the computer vision tasks are performed on the **KITTI** and **NYUD** datasets used in the research paper [Real-Time Joint Semantic Segmentation and Depth Estimation Using
Asymmetric Annotations](https://arxiv.org/pdf/1810.03272.pdf)

<br/>

**Note :** The TensorFlow version of the computer vision tasks (`KITTI` and `NYUD` folders) are W.I.P. This is because the PyTorch versions of these notebooks uses the pretrained model checkpoints and weights provided by the [authors of the paper](https://github.com/DrSleep/multi-task-refinenet/tree/master/weights) which cannot be used for TensorFlow. The PyTorch trained model can be converted to ONNX format to be loaded using TensorFlow for making inference but for the `KITTI` dataset this method causes shapes mismatch and hasn't yet been implemented and explored for `NYDU` dataset.                                              
