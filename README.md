# Pet Classifier

Pythom implementation to use a pre-trained classifier for classifying images and determine which model works best. Project done as part of Udacity Nanodegree. The three Convolutional Neural Networks used are - AlexNet, VGG, ResNet

## Scripts

To run a program like check_images.py, first open a terminal window within the Project Workspace. Next type the following and hit enter to run the program

`python check_images.py --dir pet_images/`

To run one model on images in pet_images folder and store in resnet_pet-images.txt

`python check_images.py --dir pet_images/ --arch resnet  --dogfile dognames.txt
     > resnet_pet-images.txt`

Following script runs all the three models on images in pet_images folder

`sh run_models_batch.sh`

Following script runs all the three models on images in uploaded_images folder

`sh run_models_batch_uploaded.sh`

## Result

According to my results, VGG performs best in classifying images as "dog" and "not-a-dog"
