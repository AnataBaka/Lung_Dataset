# Lung_Dataset

The purpose of this model is to determine whether in a lungs they are healthy, opaque, or have viral pneumonia contained within them.
![lung_opactiy](https://github.com/user-attachments/assets/1a8a66c7-0de2-4e4f-b3fd-161e460aedd7)
![pneumonia](https://github.com/user-attachments/assets/f81c8772-4a9b-43ea-86d7-d9d2e42dbd01)

## The Algorithm

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

## Running this project

1. First, begin by setting up an SSH conection with your Jetson Nano (with jetson-Inference coeligured) and opening a functioning terminal.
   
3. Run this commands to update your installer. You will be prompted to enter your password.
sudo apt-get update
3. Run this command to install cmsudo apt-get install git cmake
4. Use cd commands to change directories until you are in your jetson-inference/python/training/dassification/data
cd jetson-inference/python/training/classification/data
5. Download and extract dataset
[https:/www.kaggle.com/datasets/fatemehmehrparvar/lung-disease/data](https://www.kaggle.com/datasets/fatemehmehrparvar/lung-disease/data)
6. cd back to 'classification' directory, and then cd into the 'models' directory
cd..cd models
7. Run this command to download the skin cancer classification model.
git clone -recursive https://github.com/isamarquezg/skincancer
8. cd back to 'classification' directory
cd..
9. Use the following command to make sure that the model is on the nano. You should see a file called2. Make sure to include any required libraries that need to be installed for your project to run.

[View a video explanation here](video link)
