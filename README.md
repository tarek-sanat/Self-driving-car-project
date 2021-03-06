# Self driving car project
 self-driving-car Using Udacity's open source Self Driving Car simulation. 
### A Report of this project can be read here: [Report](https://drive.google.com/file/d/19vaZZIv00hmTZfFFHB_dLwIcJd8Jahnz/view?usp=sharing)


## Demo

https://user-images.githubusercontent.com/67877258/158003851-0dde49ed-b49f-4bb0-a8b6-a3d7e2dce0f9.mp4

## Description

This project uses the Udacity Self-Driving-Car simulator to train a neural network build using a model made by NVIDIA. The model takes in images from the car and predicts the correct steering wheel angle that the car should take. 


* Collected images dataset from the simulator labeled with the current speed of the car that will
be used to train the network.

* Applied augmentation and preprocessing techniques to the dataset using a Computer Vision
library to clean the dataset.

* Trained a Convolutional Neural Network on the previous dataset using Tensorflow to predict the
correct steering wheel angle that the car should take

## Technologies Used
* This project was built using Python. The tensorflow library was used to train the neural network and the OpenCV library for augmenting the images. Flask was used for the Simulator to communicate with the trained model.

<div class="row">
  <div class="column">
    <img align="left" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/640px-Python-logo-notext.svg.png" alt="drawing" width="70"/>
  </div>
  <div class="column">
    <img align="left" src="https://adventuresinmachinelearning.com/wp-content/uploads/2017/04/google-tensor-flow-logo-black-S-1024x768-1-930x620.jpg" alt="drawing" width="100"/>
  </div>
  <div class="column">
    <img align="left" src="https://editor.analyticsvidhya.com/uploads/800882.png" alt="drawing" width="80"/>
  </div>
  <div class="column">
    <img align="left" src="https://miro.medium.com/max/438/1*0G5zu7CnXdMT9pGbYUTQLQ.png" width="120"/>
  </div>
</div>
