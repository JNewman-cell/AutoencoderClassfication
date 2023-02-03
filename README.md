# AutoencoderClassfication
 I trained an autoencoder on MNIST and MVTEC datasets, one for letter recognition and one being for transistor positioning detection. The autoencoder reconstructed the images that went through the training, which allowed it to calculate the difference between the reconstruction and the prediction images. Using the differences, it can classify the images by setting a threshold difference value and using it to separate the in class and out of class images.
 
## Final Results
 As you can see on my website, jacksonnewman.netlify.app, the autoencoder can definitively classify the images, meaning it can detect the correct orientation of the transistor through the separation of differences.
