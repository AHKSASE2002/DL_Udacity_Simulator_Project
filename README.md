# DL_Udacity_Simulator_Project
This Repositry contains a Python script that defines and trains a deep learning model for a self-driving car simulation using PyTorch.

# Model Architecture
The model consists of the following layers:

    Four convolutional layers with 5x5 filters and 2x2 stride
        Conv1 with 3 input channels
        Conv2 with 24 channels
        Conv3 with 36 channels
        Conv4 with 48 channels
    Two fully connected layers
        FC1 with 100 neurons
        FC2 with 50 neurons
    Activation functions: ReLU for all layers except the last one, which is linear.

# Datasets
Found Here : [https://drive.google.com/drive/folders/1XYR5B-MVpe3I77OlgUyQZsWteE-ZNIcp?usp=sharing](https://drive.google.com/drive/folders/1JXOKqOiP0Drz08_fyuX8POa-CawHem8f?usp=drive_link)

# Saved Model
The trained model's weights and architecture are saved to a file named PTmodel.pth. You can load this model for inference in your autonomous driving system.
