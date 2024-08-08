# Lung_Dataset

The purpose of this model is to determine whether in a lungs they are healthy, opaque, or have viral pneumonia contained within them.
![lung_opacity](https://github.com/user-attachments/assets/f853fee9-d4de-450f-9888-8cf512529f69)
![pneumonia](https://github.com/user-attachments/assets/0f7abba6-b5ba-421e-b123-5f0e7615e006)


## The Algorithm

This AI was trained on images of lung x-rays with some being normal, others being opaque lungs, and the final ones having viral_pneumonia. Trained on these datasets the model is able to determine whether an image of lungs is opaque, normal, or is infected with viral pneumonia.
## Running this project

Running this project
1. Setup your Jetson Nano and Install VScode
2. Connect Jetson Nano onto your computer hotspot. Write down your Jetson Nano IP address for later use
3. Connect your VScode to your Jetson Nano using Connect Host and ssh nvidia@IPAddress
4. Open the NVIDIA home folder
5. Open the terminal and use cd jetson-inference/python/training/classification to enter the needed directory
6. Use NET=models/lungs_dataset and DATASET=data/lungs_dataset to set NET and DATASET for later reference
7. Move the picture of the lungs into the into the lungs_dataset Testing folder
8. Run the model using imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/Testing/IMAGE_NAME.jpg IMAGEOUTPUTNAME.jpg
9. Your output will be done and the image will be sent to data/lungs_dataset/test/Testing/IMAGEOUTPUTNAME.jpg

[[View a video explanation here](video link)
](https://youtu.be/wHs0Z1qPO5w)
