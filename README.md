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
<div>
### Few results of classification for main classification.
<div>
<img align="left" src="https://raw.githubusercontent.com/esha-sg/Apparel-Classification-Using-Convolutional-Neural-Networks/master/Apparel_Dataset/T_Shirts/T_Shirt1.jpg">
T-Shirt      : 0.99694 <br/>
Ladies Kurta : 0.00185 <br/>
Pants        : 0.00102 <br/>
Footwear     : 0.00011 
</div>
 <div>
<img align="left" src="https://raw.githubusercontent.com/esha-sg/Apparel-Classification-Using-Convolutional-Neural-Networks/master/Apparel_Dataset/Sarees/Saree1.jpg">
Saree        : 0.99445 <br/>
Ladies Kurta : 0.00536 <br/>
Pants        : 0.00009 <br/>
T-Shirt      : 0.00005 <br/>
</div>
</div>
   <div>
### Few results of classification for sub class tshirt
<div>
<img align="left" src="https://raw.githubusercontent.com/esha-sg/Apparel-Classification-Using-Convolutional-Neural-Networks/master/Sub_Class_TShirt/Polos/Polos1.jpg">
Polos       : 0.98160<br/>
Round Neck  : 0.01070<br/>
SweatShirt  : 0.00769<br/>
  </div>
</div>








