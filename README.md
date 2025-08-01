# YOLOv5/YOLOv9 for Fire Detection

Fire detection task aims to identify fire or flame in a video and put a bounding box around it. This repo includes a demo on how to build a fire detector using YOLOv5/YOLOv9.

<p align="center">
  <img src="results/result.gif" />
</p>

## 🛠️ Installation

1. Clone this repo 
```shell
# Clone
git clone https://github.com/spacewalk01/yolov5-fire-detection.git
cd Yolov5-Fire-Detection
```

2. Install [YOLOv5](https://github.com/ultralytics/yolov5). 
```shell
git clone https://github.com/ultralytics/yolov5.git 
cd yolov5
pip install -r requirements.txt
```

3. Or install [YOLOv9](https://github.com/WongKinYiu/yolov9.git)
```shell
git clone https://github.com/WongKinYiu/yolov9.git
cd yolov9
pip install -r requirements.txt
```

## 🔗 Reference

I borrowed and modified [YOLOv5-Custom-Training.ipynb](https://github.com/ultralytics/yolov5/wiki/Train-Custom-Data) script for training YOLOv5 model on the fire dataset. For more information on training YOLOv5, please refer to its homepage.

* https://github.com/robmarkcole/fire-detection-from-images
* https://github.com/ultralytics/yolov5
* https://github.com/AlexeyAB/darknet
