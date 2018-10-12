# codefundo
We will predict hurricane's and their intensity using data from satellite images and pressure data of areas above water bodies using a deep neural network.

First we will remove noise from the image because their might many local disturbances adding to the noise. There might be interference from the sensors as well. Then we will sharpen the image using variuos LoG filters. We will then use Convolution Neural Networks followed by multiple hidden layers. 
For training our network we will take images from previous hurricanes some 'k' days before the actual hurricane hit, and we'll try to predict the no. of days before the hurricane would  hit. 
If we take 'k' to be vry small our error would also be quite less but the essence of prediction will be lost as we won't be able to inform the local authorities. So we will have to have a trade off between 'k' and the error.
This will help in predicting hurricanes and their intensity way before they strike and henc help us be better prepared for its impact.
That would in turn minimise losses to life.
