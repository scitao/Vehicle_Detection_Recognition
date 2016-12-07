# Vehicle_Detection_Recognition
This is a Matlab lesson design for vehicle detection and recognition.  Using cifar-10Net to training a RCNN, and finetune AlexNet to classify. Thanks to Cars Dataset : http://ai.stanford.edu/~jkrause/cars/car_dataset.html

#Software

Matlab R2016b

#Doadload

cars_meta.mat : http://pan.baidu.com/s/1mi6nvr6

cifar10NetRCNN.mat : (for Car position detection)  http://pan.baidu.com/s/1geLa1V1

AlexNet_New.mat : (for Car type classify) http://pan.baidu.com/s/1bEzcYE

#Code 

You can use it to finish your task for single picture or video. Make sure your picture or video frame has 3 channels (colorful)

#Citation

3D Object Representations for Fine-Grained Categorization
       Jonathan Krause, Michael Stark, Jia Deng, Li Fei-Fei
       4th IEEE Workshop on 3D Representation and Recognition, at ICCV 2013 (3dRR-13). Sydney, Australia. Dec. 8, 2013.
       
DataSet : http://ai.stanford.edu/~jkrause/cars/car_dataset.html

#Effect

![](http://img.blog.csdn.net/20161122152409064)
![](http://img.blog.csdn.net/20161122152440557)
![](http://img.blog.csdn.net/20161122152449448)
![](http://img.blog.csdn.net/20161122152457760)
![](https://github.com/Prof-Stephencurry/Vehicle_Detection_Recognition/blob/master/pic.gif)
![](https://github.com/Prof-Stephencurry/Vehicle_Detection_Recognition/blob/master/video.gif)

Actually, The running speed of the program is a bit of slow... Hope you can try Faster-Rcnn or yolo (you only look once).
