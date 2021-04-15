# Object-detection-using-YOLOv3

This project implements an image and video object detection classifier using pretrained yolov3 models. 
The yolov3 models are taken from the official yolov3 paper which was released in 2018. The yolov3 implementation is from [darknet](https://github.com/pjreddie/darknet). Also, this project implements an option to perform classification real-time using the webcam.

## How to use?

1) Clone the repository

```
git clone https:https://github.com/MuntahaShams/Object-detection-using-YOLO.git
```

2) Move to the directory
```
cd Object-detection-using-YOLO
jupyter notebook
```

3) download yolov3 weights and place it inside weights directory
[YOLOv3 Pre-trained Model Weights (yolov3.weights)(237 MB)](http://pjreddie.com/media/files/yolov3.weights)

4) To infer on a image 
```
run imgae.ipnyb notebook
```

5) To infer on a video 
```
run video.ipnyb notebook
```

6) To infer real-time on webcam
```
run webcam.ipnyb notebook
```
