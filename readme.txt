cascade classifier: cascade classifier file to detect cars, pedestrian, stoplights, two wheelers.

data: .yaml file for datasets path

datasets: the bdd100k datain yolo's format

test_video: some videos for testing

weights: yolov5n.engine for inferencing on tensorrt
              yolov5n_4000_640.pt is trained from 4000 pictures of 640x640 pixels
              yolov5n_6000_640.pt is trained from 6000 pictures of 640x640 pixels
              yolov5n_8000_416.pt is trained from 8000 pictures of 416x416 pixels
              yolov5s_3000_640.pt is trained from 3000 pictures of 640x640 pixels
              yolov5s_5000_640.pt is trained from 5000 pictures of 640x640 pixels

convert2yolo.py: convert bdd100k labels to yolo

car_detection_yolov5.py: the main program to detect vehicles by yolov5.
                                        change your own parameters in parameters().

car_detection_cascade_classifier.py: the main program to detect vehicles by cascade classifier.
                                                          change your own parameters in parameters().