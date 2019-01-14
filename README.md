# SpeedChallenge
This is a project to determine speed of a car from a dash cam video

The python notebook (SpeedChallenge.ipynb) has the code for the process. First optical flow for consecutive frames from the training video is extracted. These optical flow images serve as the input for the custom network which outputs the speedof the car. The custom network is a deep network with multiple convolutional layers, ReLU activation and Instance normalization. 1 x 1 convolutions are used to reduce the number of channels and finally linear layers are added for prediction of a real value
