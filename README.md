## Tools and resource

1. Python - Tested on Python 3.9+
2. Tensorflow - Tested on Tensorflow 2.13.0+
3. FastAPI
4. Docker

## Steps for model training
1. First download the datasets from the following link: https://drive.google.com/drive/folders/17_vJzfcs4KFM9Nkqv1Bjt4HIpGLQYtMo?usp=drive_link
   <h1 align="center">
       <br>
       <a href="https://ibb.co/cwjFq8B"><img src="https://i.ibb.co/Qk4N0Hg/Screenshot-from-2023-12-21-18-26-39.png" alt="Screenshot-from-2023-12-21-18-26-39" border="0"></a>
       <br>
   </h1>

2. Pre-processing the data and clean it up by separating the data into training, validation, and test.
   <h1 align="center">
       <br>
       <a href="https://ibb.co/HhTh3c6"><img src="https://i.ibb.co/qJYJVHK/Screenshot-from-2023-12-21-18-27-42.png" alt="Screenshot-from-2023-12-21-18-27-42" border="0"></a>
       <br>
   </h1>
5. Then, rescale the image and also determine the target image size that we will use. We use a target size of 224px.
6. After splitting into 3 parts, then each data is ready for model training.
7. For our training, we use the existing pre-trained model Xception as our base model.
8. We also created our own model by adding a 2D Convolutional layer, MaxPooling, and also added 2 Neural Layers.
9. With this model, we can predict a class from the equipment data that users will use later.
10. We do deployments using Docker, FastAPI, and also Cloud Run.
