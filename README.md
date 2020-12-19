# YOLO-for-HellChef

## Abstract
In our project, we are applying CNN techniques to detect and recognize the fruits and vegetables that are available in the house and recommend the dish that can be prepared using the main key ingredients. We have many applications (app) for side chef, super cook where the recipes and other steps are present. However, we need to manually search for the dishes that matches with the ingredients we have in our house. Many of people doesn’t know the ingredients names and it has been a challenge to many people even our parents. In our application, the user can take the pic of the items (vegetables and fruits) that are available in his refrigerator or in the house, using the Hell-chef app there is a smart camera feature for it. The captured image goes to the CNN and identify the items or ingredients and lists the recipes where the user can choose the dish they want to make. This algorithm used in the application provides accurate results and high accuracy.

We train the model using the custom dataset of fruits and vegetables. The ready to use trained weights are available in the GitHub repository of coco weights. However, they cannot be used for our model since we are using the custom dataset and train the network model. Since the dataset is huge, we use google drive to store the data.

## How it works
* First we need to upload the file in drive, since the input image and training weights will be stored in the drive
  <br/>[Drive Files](https://drive.google.com/drive/folders/1wzi36eTOIGBf7Nd0KfBZh1GMlZ5PJ9MP?usp=sharing "yolov3")
* uncomment the code in the Google Colab file
* Run the code one by one
* As files are present in the google drive they will be copied and the YOLO starts training
* The trained weights are stored in Backup file where we use to test the network

## HellChef App Repo
[HellChef App](https://github.com/whosethebos/HellChef.git)

<br/>[References](https://youtu.be/_FNfRtXEbr4)
