# Fashion-MNIST

This repository consists of a Jupyter Notebook containing code for a convolutional neural network model created in PyTorch to be used for classifying images from the Fashion-MNIST dataset.

The code can be executed either on a CPU or on a GPU (for example, by clicking on the 'Open in Colab' button at the top of the notebook).

The model has been saved to a file called `convNet.pth`.

## To load and use the saved model in your own work:

1) Copy the definition of the convNN class from the Jupyter Notebook to your own Python module.
2) Execute the following code in PyTorch:

```
model = convNN()
model.load_state_dict(torch.load("convNet.pth"))
```
