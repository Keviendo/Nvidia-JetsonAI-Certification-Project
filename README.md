# Nvidia-JetsonAI-Certification-Project

# YOLO Object detection For nivida jetson 
I am using the famous YOLO object detection that uses neural networks. The YOLO object detection is famous for training using the COCO dataset which consist of lots of daily objects. 
# basic prerequisites
## Jetson configuration
Please install Conda and make sure you have the right version. Jetson nano  
https://github.com/Archiconda/build-tools/releases/tag/0.2.3

## Extra Downloads
I am using the tiny object model. This allows faster computation for movements like tracking a person running. 
 https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v4_pre/yolov4-tiny.weights
https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v4_pre/yolov4-tiny.weights

# Personal steps 

Clone this repo on your jetson
````
git clone https://github.com/theAIGuysCode/yolov4-deepsort
```` 
Set conda or virtual environment 
```` 
conda env create -f conda-cpu.yml
conda activate yolov4-cpu
```` 
