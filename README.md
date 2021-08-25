# Face-Gender-Recognition
A face+gender recognition app by Akshit Mehra.

## Description
This app uses LBPH Face Recognition which uses knn in backgroud to differetiate and identify the face from the already existing dataset.
The gender_test file will be able to differentiate Male and Female of any person irrespective if they are stored in the dataset or not

## Making files
Make an empty folder named "dataset" and an empty txt file called "userid.txt".

## All the files explained
1. The dataset folder will be storing all the images of the users.
2. All the users will have a UserID that needs to be entered when capturing the photos, this is stored in userid.txt.
3. face_recog_dataset will capture images of a user using OpenCV and will store them in the dataset folder corresponding to the UserID.
4. face_recog_train will train the model on all the images in the dataset using LBPHfacerecognizer And OpenCV. 
5. face_test will classify the user in already existing dataset.
6. gender_test will tell the gender of any new user depending upon already existing data. It's a modification of face_test.
7. haarcascade_frontalface_default is used to detect the face and capture the image. 

## Steps to run
Make the 2 files mentioned above
Create the dataset by running face_recog_dataset.
Then add the name you want to display with the corresponding user in face_test file and add the gender of the person in gender_test file.
Run face_recog_train to train the model.
Run face_test to see the code working.
Optional: After a adding some users, you can run the gender_test file to determine the gender of any new person that is not in the dataset.

