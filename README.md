# Repository

The code is for training a DeepLabV3+ model for Semantic Segmentation of Tissue

## Installation

The code is written and tested on MATLAB R2020a.

Install following Add-ons

```bash
Deep Learning Toolbox
Computer Vision Toolbox
```

## Training


Change the directories for "Training dataset" and "Validation Dataset" in "training.mlx".

Run the live script and save the neural network.

## Testing


For testing, load the "nn.mat" file (or the one generated by "training.mlx") in the workspace and run 
