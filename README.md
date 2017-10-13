# A ConvNet images classifier using CIFAR10 dataset

## Why?
This repository have been created only for learning purposes (PyTorch). This is not a real production trained ConvNet.

## Requirements

- Python2.7 or Python3.5+
- PyTorch installed and all its dependencies

## Usages

**Train the neural network**  
run `python main.py`

**Use the classifier**
run `python classifier.py`

## How it works?

The CNN (convolutional neural network) model is in the `convnet.py` file. The file `main.py` is the trainning script. It will train the CNN and save the weights in the `trained_model_weights` file. Then, the `classifier.py` is the script that use the trained CNN to simulate a classifier: give images as inputs, get the predictions and copy/paste the images in the "right" folders (`final_gallery`) according to the predictions.
