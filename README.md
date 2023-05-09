# Animal-Image-Classification-using-CNN
In this project we aim to classify images of animals by training the VGG-16 transfer learning model using Covolutional Neural Network for a dataset of about 5000 images that include 10 classes of animals.

**Problem statement**
Animal detection and recognition are still a difficult challenge and there is no unique method that provides an  efficient solution to all situations. 
Generally, features from the animal that belongs to a certain class are used to train a certain classifier. Then, given a new input image, the classifier will be able to decide if the sample is the animal or not. 
To better understand the complexities of natural ecosystems and better manage and better protect them, it would be helpful if we can differentiate the animals based on their attributes and characteristics.

**Dataset:**
<br>
https://www.kaggle.com/alessiocorrado99/animals10
This dataset contains  28000 animal pictures of 10 different categories taken from google images.
The categories are  Dog, Cat, Horse, Spyder, Butterfly, Chicken , Sheep, Cow, Squirrel, Elephant.
Each category has  around 2000-4000  images of a specific  animal .
Each image is a 224 * 224 * 3 image which will be our input.

**Why use CNN model in particular?**
<br>
Image classification involves the extraction of features from the image to observe some patterns in the dataset. 
Using an ANN for the purpose of image classification would end up being very costly in terms of computation since the trainable parameters become extremely large.

**How CNN works?**
<br>
The CNN model which works on building a network, like a funnel, and finally gives out a fully-connected layer where all the neurons are connected to each other and the output is processed. 
CNNs are one of the best learning algorithms for understanding and analyzing image content that has shown high performance in image segmentation, classification, detection, and retrieval related tasks.

**VGG16 Architecture**
<br>
VGG 16  is a CNN  architecture  which was used to win ILSVR  (imagenet) competition.
It is consider to be one of the excellent vision model architecture till date.
It follows this arrangement of convolution and max pool layers consistently throughout the whole architecture .
This has 16 convolution layers
