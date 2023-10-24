Image classification is one of the supervised machine learning problems that aims to categorize the images of a dataset into their respective categories or labels. Classification of images of various dog breeds is a classic image classification problem. So, we have to classify more than one class that’s why the name multi-class classification, and in this article, we will be doing the same by making use of a pre-trained model InceptionResNetV2, and customizing it.
--------------------------------------------
--------------------------------------------
--------------------------------------------
Transfer learning: Transfer learning is a popular deep learning method that follows the approach of using the knowledge that was learned in some task and applying it to solve the problem of the related target task. So, instead of creating a neural network from scratch we “transfer” the learned features which are basically the “weights” of the network. To implement the concept of transfer learning, we make use of “pre-trained models“.
--------------------------------------------
Necessities for transfer learning: Low-level features from model A (task A) should be helpful for learning model B (task B).
--------------------------------------------
Pre-trained model: Pre-trained models are deep learning models which are trained on very large datasets, developed, and are made available by other developers who want to contribute to this machine learning community to solve similar types of problems. It contains the biases and weights of the neural network representing the features of the dataset it was trained on. The features learned are always transferrable. For example, a model trained on a large dataset of flower images will contain learned features such as corners, edges, shape, color, etc.
--------------------------------------------
InceptionResNetV2: InceptionResNetV2 is a convolutional neural network that is 164 layers deep, trained on millions of images from the ImageNet database, and can classify images into more than 1000 categories such as flowers, animals, etc. The input size of the images is 299-by-299.
--------------------------------------------
==>The dataset used comprises 120 breeds of dogs in total.
==>Each image has a file name which is its unique id.
==>Train dataset ( train.zip ): contains 10,222 images which are to be used for training our model
==>Test dataset (test.zip ): contains 10,357 images which we have to classify into the respective categories or labels.
==>labels.csv: contains breed names corresponding to the image ID.
==>sample_submission.csv: contains the correct form of sample submission to be made
...
...