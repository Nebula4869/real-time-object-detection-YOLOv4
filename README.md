# tensorflow_YOLOv4
A tensorflow implementation of YOLOv4, including training on VOC and real-time detection demo
### Environment

- python==3.6.5
- tensorflow==1.12.0
- opencv-python

### Getting Started

#### Training on VOC

Run "train_voc.py" after placing the database in the correct position.

#### Real-time detection demo

1. Download [yolov4.weights](https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.weights) and place in the "weights" folder.
2. Run "convert_weights.py" to convert Darknet's .weights files into tensorflow's .ckpt files.
3. Run "demo.py" to detect from video or camera.

