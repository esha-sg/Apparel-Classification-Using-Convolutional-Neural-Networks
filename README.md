# Apparel-Classification-Using-Convolutional-Neural-Networks

Convolutional neural networks are the state of the art currently at recognising objects in images. Here the last layer of the Google's inception model is trained to recognise apparels.

## Data Collection

Around 800 images of sarrees, footwear, t-shirts, pants and ladies kurta have been used to train the inception model. The data was collected from Myntra and has been used for research and educational purpose only. Apparel_Dataset folder contains sample images.

Further more data has been collected for apparels such as sweat shirts, polos and round necks. Sub_Class_Tshirt contains a few samples of these images.

## Training
The first level of training was done similar to [this](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/).
The results are amazing with a test accuracy of nearly 97%.

Further, inception model was trained similarly on Sub_Class_Tshirt dataset. Since there are just minute differences between polos and round necks i.e just the presence or absence of collar the accuracy of this model was bad compared to the former but was still very good at around nearly 93%.

## Results








