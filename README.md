# Helmet Detection using YOLOV3
Its a simple YOLO model to detect and count the number of people wearing helmet in a image. this model can be used to detect the intrusion or to find the people ridding bike without helmet.

Here you can read my post in detail  https://medium.com/@vijaysingh_60587/train-your-own-custom-model-for-helmet-detection-object-detection-using-yolo-f53a48066d7a

Getting Started
#### This code is very simple and with the help of little manipulation, you can count the number of detection for a particular detection.
#### or extract the co-ordinates of bounding boxes. download the models, create necessary files and give full path to the models and folder names and run the python script.

#### training:  
  if you want to train your own model, follow the [darknet](https://github.com/AlexeyAB/darknet).
Prerequisites  
install python3.  
install pip3.  
install opencv.( sudo pip3 install opencv-python ).  

install other liberaries  if missing.  


After setting up the paths.  
change the path of classfile in line 19,  
change the path of configuration file in line 25,  
change the path of weights in line 26  
change the output folder name in line 133 where you want to keep your output files.  
change the name of folder in line 150 for input images.  
, it's ready to run.  
open terminal and python3 Helmet_detection_YOLOV3.py  

#### link to files.  
[model](https://drive.google.com/file/d/1_xBdP1GRK4i7yzJP8_a5GWaejZZKjdyI/view?usp=sharing)  
[cfg](https://drive.google.com/file/d/119l1wonij3kXcuyAHC6-jRTw1NT0FzFH/view?usp=sharing)  
[obj.names](https://drive.google.com/file/d/1eSA8XVuzCe9Ka63v-HEWx7Hxo8z_cpaF/view?usp=sharing)  
If everything went well. you will get results like this  
![img1](https://github.com/BlcaKHat/yolov3-Helmet-Detection/blob/master/test_out/img3.jpg)  
![img2](https://github.com/BlcaKHat/yolov3-Helmet-Detection/blob/master/test_out/img4.jpg)  
![img3](https://github.com/BlcaKHat/yolov3-Helmet-Detection/blob/master/test_out/img.jpg)  


