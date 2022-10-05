# Distance Detection for Self-driving Vehicle Deploy Through Fixed Stereo Vision Method

An inter-vehicles distance measurement that runs on FPGA board will be introduced in this article. The proposes for this study is to verified the practicality for this inter-vehicles distance measurement building on the exist object recognition system by the potential error marking on the center point. In this report, we will use stereo vision method as our inter-vehicles distance measurement
which require less computing loading for our target device. In this article, we will be stepping over explaining how distances prediction
and how we fixed it with our formula. Fixing the error rate for the distance prediction from 40% down to approximately 5%.

## Yolo v4 and v4-tiny for Windows and Linux

## (neural networks for object detection)

Paper Yolo v4: https://arxiv.org/abs/2004.10934

More details: [medium link](https://medium.com/@alexeyab84/yolov4-the-most-accurate-real-time-neural-network-on-ms-coco-dataset-73adfd3602fe?source=friends_link&sk=6039748846bbcf1d960c3061542591d7)

Manual: https://github.com/AlexeyAB/darknet/wiki

Discussion: 
 - [Reddit](https://www.reddit.com/r/MachineLearning/comments/gydxzd/p_yolov4_the_most_accurate_realtime_neural/)
 - [Google-groups](https://groups.google.com/forum/#!forum/darknet)
 - [Discord](https://discord.gg/zSq8rtW)

About Darknet framework: http://pjreddie.com/darknet/

[![Darknet Continuous Integration](https://github.com/AlexeyAB/darknet/workflows/Darknet%20Continuous%20Integration/badge.svg)](https://github.com/AlexeyAB/darknet/actions?query=workflow%3A%22Darknet+Continuous+Integration%22)
[![CircleCI](https://circleci.com/gh/AlexeyAB/darknet.svg?style=svg)](https://circleci.com/gh/AlexeyAB/darknet)
[![TravisCI](https://travis-ci.org/AlexeyAB/darknet.svg?branch=master)](https://travis-ci.org/AlexeyAB/darknet)
[![Contributors](https://img.shields.io/github/contributors/AlexeyAB/Darknet.svg)](https://github.com/AlexeyAB/darknet/graphs/contributors)
[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](https://github.com/AlexeyAB/darknet/blob/master/LICENSE)
[![DOI](https://zenodo.org/badge/75388965.svg)](https://zenodo.org/badge/latestdoi/75388965)
[![arxiv.org](http://img.shields.io/badge/cs.CV-arXiv%3A2004.10934-B31B1B.svg)](https://arxiv.org/abs/2004.10934)
[![colab](https://user-images.githubusercontent.com/4096485/86174089-b2709f80-bb29-11ea-9faf-3d8dc668a1a5.png)](https://colab.research.google.com/drive/12QusaaRj_lUwCGDvQNfICpa7kA7_a2dE)
[![colab](https://user-images.githubusercontent.com/4096485/86174097-b56b9000-bb29-11ea-9240-c17f6bacfc34.png)](https://colab.research.google.com/drive/1_GdoqCJWXsChrOiY8sZMr_zbr_fH-0Fg)


* [YOLOv4 model zoo](https://github.com/AlexeyAB/darknet/wiki/YOLOv4-model-zoo)
* [Requirements (and how to install dependecies)](#requirements)
* [Pre-trained models](#pre-trained-models)
* [FAQ - frequently asked questions](https://github.com/AlexeyAB/darknet/wiki/FAQ---frequently-asked-questions)
* [Explanations in issues](https://github.com/AlexeyAB/darknet/issues?q=is%3Aopen+is%3Aissue+label%3AExplanations)
* [Yolo v4 in other frameworks (TensorRT, TensorFlow, PyTorch, OpenVINO, OpenCV-dnn, TVM,...)](#yolo-v4-in-other-frameworks)
* [Datasets](#datasets)


## Hardware Setups


## Algorithm Implement

