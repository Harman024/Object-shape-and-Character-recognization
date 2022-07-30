# Object-shape-recognization
The above is a comparison between a ANN and VGG-16 architecture to get a DL model to determine the shape of the given images.
Below link attached include the data and pre-trained model to be used directly:
https://drive.google.com/drive/folders/1-WiUkcXf1q09-hQ_wAKNLUl04i6UkmBj?usp=sharing

First the given data of images is augmented using Augumentor.ipynb to prevent overfitting.

Model.ipynb: An ANN model is trained and run to get our accuracy and plot confusion matrix for itself.

premodel.ipynb make use of VGG-16 architecture using transfer learning. Tarining the model with certain accuracy and confusion matrix is obtained.

Difference between accuracy, loss and other factors are found.

