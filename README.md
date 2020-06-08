# FaceRecognition
Face Recognizer in python using OpenCV
OpenCV is required to be installed.

Step 1:
Download the repo and extract them in the same folder

Step2:
Change the path names to your respective files' path names, and label names to your names.

Step3:
add a folder called MyImages (or whatever you want to call it; you'll have to change the path accordingly)
add a folder called 0 to MyImages.

Step4:
Change the path of saving the photos in the data_set.py file to "C:\\<your path here>\MyImages\0" to capture the first persons face.
Run the data_set.py file. It will capture frames from the video input. Capturing more video will increase the accuracy of your model but it will take more time to train.
Make sure that all the photos have been saved in the 0 folder.
This was for the first person.
You can capture the data from many persons similarly.
eg: the second person's folder will be "1" in MyImages, and you will change the path of saving Images in data_set.py to "C:\\<your path here>\MyImages\1"
you can add the names in the name variable like so: name={0:"Subodh",1:"Manish",2:"Bhavana"}
  
Step5:
It's time to train your model.
Run the traiining.py file after changing the path test image to the location of an image of the person whose data you had earlier stored.

Step6:
After you're done training, you can:
a)Run the load_model_image.py file and feed an image of the person's face you want to recognise, or
b)Run the load_model_video.py file to give Video input from your webcam to provide real-time input.

Have fun!


