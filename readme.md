

# Project Name

An Object Detection Application Let Kids Learn with AI

## Features

This is an object detection application based on [YOLOv5 v6.1](https://github.com/ultralytics/yolov5/tree/v6.1) and [COCO dataset](https://cocodataset.org/#home).
It can show informations about the detected objects. Also a it can read those descriptions by [Google TTS](https://cloud.google.com/text-to-speech).
The way of calling YOLO's API is from [Javacr](https://github.com/Javacr/PyQt5-YOLOv5), the usage of parts of source code is under author's knowledge and agreement.


## Installation
Python Version : 3.8.15

Firstly if you want to use under a NVIDIA GPU，you should download [CUDA](https://developer.nvidia.com/cuda-downloads) by yourself, Or you can only use cpu (it can works as well, but with lower FPS).


Start by 
```
pip install -r requirements.txt
```

If you want to have a better voice, begin with 
```
python mainVer2.py
```
It is using [Google TTS](https://cloud.google.com/text-to-speech)

If you want to run it offline without internet connection, begin with 
```
python mainVer2Local.py
```
It is a Microsoft TTS included in your Win10 or Win11.

There are no differences beside the tts API. 


## Usage Examples

Provide code snippets or screenshots demonstrating how to use your project. For example:
