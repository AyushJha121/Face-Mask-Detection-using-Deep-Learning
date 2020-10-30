# Face-Mask-Detection-using-Deep-Learning
This is a face mask detector built using Keras,Tensorflow, MobileNet and OpenCV.
With further improvements these types of models could be integrated with CCTV cameras to detect and identify people without masks.

The face mask detector didn't use any morphed masked images dataset. The model is accurate, and since the MobileNetV2 architecture is used, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.


## Installation
Install the required files using 
>pip install -r requirements.txt 
## Training the data
The data set has been taken from Kaggle and contains two folders masked and unmasked pictures to train our model.
One can check the accuracy of the model by using the following command in cmd
> py train_mask_detector.py

An image will be auto generated with the name plot.png which I have attached it shows the accuracy of our model.
## Real Time Detection
For viewing the results you need to have a webcam installed on your PC
Use the following script to run the program
> py detect_mask_video.py

You can try out different angles and the program will show the results the confidence value above the square box.
