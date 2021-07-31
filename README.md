This is an image classifier using the SVHN dataset. It classifies input images of digits from 0 to 9 using neural networks.  

The SVHN dataset has labeled real pictures of house numbers from Google Street View images. 

I compare the use of 2 types of neural networks. A MLP and a Convolutional NN:

The MLP uses 144,266 parameters to achieve a training loss of .947 and an accuracy of .77. 
The Convolutional NN, just needs 12,538 parameters for a training loss of .404 and accuracy of .89 

It is done with Tensorflow 2. 

Dataset source:
http://ufldl.stanford.edu/housenumbers/
Yuval Netzer, Tao Wang, Adam Coates, Alessandro Bissacco, Bo Wu, Andrew Y. Ng Reading Digits in Natural Images with Unsupervised Feature Learning NIPS Workshop on Deep Learning and Unsupervised Feature Learning 2011.

