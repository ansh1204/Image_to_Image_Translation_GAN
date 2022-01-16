## CS 760 - Machine Learning Project Code

### GAN
Follow the instructions to execute the code. 

1. Download maps.tar.gz dataset from the following link - http://efrosgans.eecs.berkeley.edu/pix2pix/datasets

2. Extract data and update the path variables in the parameter block (Cell 2) in the ipynb notebook.

Note: The code has been shared for the cGAN + PatchGAN implementation with MSE Loss function. To see the results for MAE Loss function change the loss function(Cell 8).


### Style Transfer
We also examine how a style transfer architceture compares to generative model developed by us. For this comparison we use the implementation [https://github.com/leongatys/PytorchNeuralStyleTransfer](https://github.com/leongatys/PytorchNeuralStyleTransfer), and use the satellite image as the "content" and map view as the "style" image. The detailed explanation and results are presented in the report.
