# Facial-Expression-Prediction
<p align="center">
<img src = "output/image2.jpg" width = 400 height=300>
</p>


      
   
   One of the most exiciting feild in Artificial Intelligence is working with images and video(Video is nothing but set of images). I wanted to do image classification. One of such project is Facial Expression classification.
   
The aim of the project is build a Deep learning network model to train and predict expression of an image and live stream video.

1. Image Augumentation
2. Design Convultion Neural Networks
3. Train the images and get the trained weights of h5 file
4. Use trained weightsfor prediction

Tools used:
* python notebook
* Keras 
* openCV.
  
  The data consist of 48x48 size of picture in both training and validatation dataset with 7 facial expression namely Happy, Sad, Neutral, Surprise, Disgussed and Fear. These images are in grayscaled. These images are augumented first by rotating and scaling and zooming etc. Then trained it in Convulution neural networks, got trained weights. 
    
    Finally, prediction done on picture of interest / live stream by using learned weights of h5 file. 
  epochs used: 25, but because of early stopping as **Stopping criteria** it stopped at 14 epochs
  
  *Activation Function: LeakyRelu, elu*
  *kernel initializer: glorat_uniform*
  *This text is italicized*
 
 I have got
  * **Accuracy: 55%**
  * **loss    : 0.98**
  
  Since i got 55% accuracy, predictions are not much improved
  
  
  **Future Work:** 
  To get better accuracy I want to do tuning hyper-parameter and train the model with higher resolution images.

  
  
       
       
        
       
           

      
