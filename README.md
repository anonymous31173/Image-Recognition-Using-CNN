# Image-Recognition-Using-CNN
Distinguish between animals or humans, with proper datasets. 


1.Link for the dataset used :
  http://www.superdatascience.com/wp-content/uploads/2017/04/Convolutional_Neural_Networks.zip

2.Dataset included:
Images for:
  Cats
  Dogs
 
Test Sets: 
  Cats: 1000
  Dogs: 1000
Train Sets: 
  Cats: 4000
  Dogs: 4000
  
Libraries used: 
- Keras 
- scikit-learn 
- Tensorflow

Program run on:
- Spyder
- Python 3.5

Steps Applied : 
1. Convolution 
2. Pooling 
3. First Two Steps repeated to increase accuracy 
4. Flattening 
5. Full Connection Establishment 
6. Fitting Image to CNN


NOTE: *The program was run on windows 10, 64 bit. The epoch rate was pretty slow, to fix the issue, in fit_generator, 'steps_per_epoch' and 'validation_steps' were divied by its batch_size. It decreased the overall execution time.*
Overall accuracy of the Test set to Training set : 
'0.8870:0.8115'
Accuracy may differ on different systems.
