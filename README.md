# AUTOMATIC-LICENSE-PLATE-RECOGNITION-FOR-ETHIOPIAN-ROADS-USING-YOLO
If you want to test the already trained file you can use my_data folder all the trained weights for both yolov3 and yolov4 had it in case of license plate detection and recognition.
#all the weight files which are trained by me can find in yolo-utils folder
#you can add new or your custom dataset  test images for detection in detectiontestpic folder, or you can use my own test images which founds in the folder 
I separate the code in real-time and not real-time which means if you run real-time code you can use  it for videos however if you run  non real-time code you can only use for images 
#after that you can test the images by running the python file  on jupytr  I have already uploaded the necessary file to test the detection and the recognition . for testing on real-time on videos use the google colab python file which I mention in the next part .
#starting training from scratch 
if you want to train from scratch which lets you use another version of yolo use the google colab with the uploaded datasets , I already uploaded  labeled datasets with corresponding  images  for both  detection and recognition step  in zip file and change all yolo version codes to use in  specific yolo version.
#use the uploaded Google_colob file "Google_colab_plate_detection_YOLOv3&v4_Custom_Object_Detection" and "Google_colab_plate_recognition_YOLOv3&v4_Custom_Object_Detection", by opening this file on google colab you can run the code and use it to train the custom dataset or new version of yolo.
#you can test real-time videos for Ethiopian license plate detection by running the below code which finds in … file 

./darknet detector demo data/obj.data cfg/yolov3_detection_training.cfg data/yolov3_detection_training_last.weights -dont_show data/img-3.MOV -out_filename img-3result.MOV
I hope this can help you to detect and recognizes Ethiopian license plates.

