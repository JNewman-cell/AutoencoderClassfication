# AutoencoderClassfication
 I trained an autoencoder on MNIST and MVTEC datasets, one for letter recognition and one being for transistor positioning detection. The autoencoder reconstructed the images that went through the training, which allowed it to calculate the difference between the reconstruction and the prediction images. Using the differences, it can classify the images by setting a threshold difference value and using it to separate the in class and out of class images.
 
## The Model
 The model I created consisted of an encoder and decoder layer, with each of them containing 3 convolution and 2 activation layers, which made it around 220,000 parameters in the entire model. I used these layers because the goal of the autoencoder is to extract the significant features of the image itself, so a bigger neural network would not have been any better at classifying.
 
## Final Results
 As you can see on my website, jacksonnewman.netlify.app, the autoencoder can definitively classify the images, meaning it can detect the correct orientation of the transistor through the separation of differences.
