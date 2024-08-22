# Development-and-Enhancement-of-Text-to-Image-Diffusion-Models-Using-CFG-and-EMA
This repository contains the code and resources for the dissertation project titled "Development and Enhancement of Text-to-Image Diffusion Models Using CFG and EMA." The project explores the application of Classifier-Free Guidance (CFG) and Exponential Moving Average (EMA) techniques to enhance the performance of text-to-image diffusion models, particularly focusing on the stable diffusion v1.4 model. This work was conducted as part of the MSc in Artificial Intelligence program by Rajdeep Roshan Sahu at Queen Mary University of London.

### Project Overview
This project focuses on the development and enhancement of text-to-image diffusion models using Classifier-Free Guidance (CFG) and Exponential Moving Average (EMA). The primary objective is to improve the performance and stability of diffusion models, particularly the Stable Diffusion v1.4 model, through the integration of EMA during training.

#### Author
Rajdeep Roshan Sahu
MSc in Artificial Intelligence, Queen Mary University of London

## Installation Instructions
##### 1. Clone the Repository:
```bash
git clone https://github.com/Rajdeep108/Development-and-Enhancement-of-Text-to-Image-Diffusion-Models-Using-CFG-and-EMA.git
cd Development-and-Enhancement-of-Text-to-Image-Diffusion-Models-Using-CFG-and-EMA
```
##### 2. Install Required Packages:
Ensure that you have Python installed (preferably Python 3.7 or higher). Install the required Python packages by running:
```bash
pip install -r requirements.txt
```
The requirements.txt file contains all the necessary dependencies for this project.

### Usage
To run the code and experiment with the models, follow these steps:
#### Model Setup:
-The baseline model used is Stable Diffusion v1.4, which is imported and configured from Hugging Face. You can access the base model from Hugging Face here.
-The CIFAR-100 dataset is used for training, and it is preprocessed to match the model’s expected input size.
#### Training the Model:
-The training process involves the use of EMA to stabilize and improve model performance.
-The baseline model was trained for 5 hours, and the trained model was saved. The training loops and intermediate outputs have been cleared to reduce disk usage.
##### Using the Enhanced Model:
- The enhanced model can be downloaded directly from the following QMUL OneDrive link.
## Model Details
#### Baseline Model
- Model: Stable Diffusion v1.4
- Dataset: CIFAR-100
#### EMA Integration
- An EMA class was defined to facilitate the integration of exponential moving averages during training. This helps in stabilizing the training process and improving model convergence.
#### Results
- All model outputs, including images generated by the baseline and enhanced models, are included in the supporting documents.
- The presentation and real images used for evaluation are also provided.
