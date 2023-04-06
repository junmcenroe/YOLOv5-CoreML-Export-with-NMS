# YOLOv5-CoreML-Export-with-NSM


This export-coreml-nms.py can export .mlmodel with NMS from .pt on recent yolov5 repo.

Usage on GoogleColab

!git clone https://github.com/ultralytics/yolov5.git

!pip install coremltools==6.2

!git clone https://github.com/junmcenroe/YOLOv5-CoreML-Export-with-NMS.git

import os,shutil

shutil.copy("/content/YOLOv5-CoreML-Export-with-NMS/export-coreml-nms.py", "/content/yolov5/export-coreml-nms.py")

cd yolov5

!python export-coreml-nms.py --img-size YourImageSize --weights YourBest.pt --include "coreml"

