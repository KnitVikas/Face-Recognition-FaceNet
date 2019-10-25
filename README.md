# Face-Recognition-FaceNet

# Face detection using-FaceNet
 The problem is to recognize the faces given in the images.Here i am having the dataset  the images of arount 17-18 for each
 face we want to detect.The order of the directory must be in the same sequence as given in the readme file.The Multi-task    Cascade Convolutional Neural Network (MTCNN) is used to crop the faces from the images.The face embedding of the croped faces is than find out by the FaceNet model of the google. The embeddings are than classify by the SVM classifier to classify the images.
 The FaceNet model can be found out here: https://drive.google.com/open?id=1Iz0xGKelA0pB-y3v-PrY-HtHjPP0xQxb
 
 
  # Loading the dataset:
The complete path of train and the test folder must be give as required mention in the readme file.
the faces are extracted ffrom the images and are stored in as arrays avery cropped images is having the corresponding labels in the 
Y_arrays.Both os the ararays are the gien to the facenet to find the embeddings.

Data set must be in this order.
main folder
train
   
    image_class1
    image_class2
    image_class3
    image_class4
    image_class5

validation
   
   
     image_class1
     image_class2
     image_class3
     image_class4
     image_class5
    
# Training the embeddings
on the SVM classifier we are going to train our embeddings we get above.than on passing the image to the model we could ge the
prediction of the model.



# Training the embeddings
on the SVM classifier we are going to train our embeddings we get above.than on passing the image to the model we could ge the
prediction of the model.


:
The complete path of train and the test folder must be give as required mention in the readme file.
the faces are extracted ffrom the images and are stored in as arrays avery cropped images is having the corresponding labels in the 
Y_arrays.Both os the ararays are the gien to the facenet to find the embeddings.

Face Verification. A one-to-one mapping of a given face against a known identity (e.g. is this the person?).
Face Identification. A one-to-many mapping for a given face against a database of
Face recognition is the general task of identifying and verifying people from photographs of their 

References:
