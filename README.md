# Image Classification Project: Natural and Urban Scenes
This repository contains the necessary files and instructions to reproduce an image classification project using Transfer Learning on Google Colab. The goal is to accurately classify images into one of six categories: Building, Forest, Glacier, Mountain, Sea, and Street.

The project was executed entirely within a single Google Colab notebook, where the dataset was cloned and processed on the fly.

## Project Setup and Execution
1. Requirements
- Google Account: Required to access Google Colab.
- Computational Resources: Google Colab provides free access to GPUs (highly recommended for faster training).
- Dependencies: All required Python libraries (PyTorch, torchvision, etc.) are installed within the notebook itself.

## Dataset Source
The raw data is acquired directly via git clone from the following public repository:
``
https://github.com/fafilia
``

# Conclusion
The ResNet model was determined to be the superior choice for this project, achieving a higher final validation accuracy in significantly less training time.
