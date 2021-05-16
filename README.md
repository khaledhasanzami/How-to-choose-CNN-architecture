# How to choose CNN architecture (MNIST)

## Data
### Dataset:
- The dataset used in the project is named **[THE MNIST DATABASE of handwritten digits](http://yann.lecun.com/exdb/mnist/)**.
- The dataset comes preloaded in Keras, in the form of a set of four Numpy arrays.
## Dataset properties:
- Total number of images: 70K
- Training set size: 60K images 
- Test set size: 10K
- Number of classes: 10 (Digits from 0 to 9)
- Image size: 28x28 pixels
## Files
There are 3 types of files in the repository:
- Digit recognition CNN.ipynb explains a normal CNN architecutre and data augmentation for handwritten digit recognition 
- readme.md explains the repository
- Best CNN.ipynb explains ways to fine tune a CNN model for best architecutre.
## Results:
- Basic CNN model: **Accuracy 99.01%**
- Basic CNN model + Data augmentation: **Accuracy 97.68%**
- After adjusting number of convolution layers: **Accuracy 99.270%**
- After choosing best channel size: **Accuracy 99.350%**
- After choosing best number of dense layer neuron: **Accuracy 99.290%**
- After adjusting neuron dropout: **Accuracy 99.350%**
- After the use of two 5x5 feature maps (for one two 3x3 replacement) with batchnormalization and data augmentation: **Accuracy 99.630%**
## Collaboration direction:
- A perfect 100% accuracy is most desirable. Anyone with 99.630% or more is encouraged to contribute.
