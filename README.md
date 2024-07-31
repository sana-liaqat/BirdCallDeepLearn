# BirdCallDeepLearn
## Capuchinbird Call Detection
This project is focused on detecting Capuchinbird calls from audio recordings using deep learning techniques. The main steps involved include preprocessing audio data, training a convolutional neural network (CNN), and making predictions on new audio recordings.

## Table of Contents
1. Installation
2. Data Preparation
3. Usage
4. Model Training
5. Prediction
6. Results

## Installation
### Clone the Repository
Start by cloning this repository to your local machine and navigate into the project directory.

### Set Up a Virtual Environment
Create and activate a virtual environment to manage dependencies.

### Install Dependencies
Install the required packages listed in the requirements.txt file.

## Data Preparation
Organize Your Data by placing your audio files into the data directory with the following structure:

1. data/Parsed_Capuchinbird_Clips for clips of Capuchinbird calls.
2. data/Parsed_Not_Capuchinbird_Clips for clips without Capuchinbird calls.
3. data/Forest_Recordings for longer recordings from forest environments.

## Usage
1. Loading and Preprocessing: Preprocess your audio files by converting them to a format suitable for deep learning, such as spectrograms.

2. Creating Datasets: Organize your audio data into training and testing datasets.

## Model Training
1. Building the Model: Design and compile a convolutional neural network (CNN) to classify Capuchinbird calls.
2. Training the Model: Train the model on your dataset and monitor performance metrics such as loss, precision, and recall.

## Prediction
1. Making Predictions: Use the trained model to make predictions on new audio recordings.
2. Processing Results: Process and analyze the predictions to identify Capuchinbird calls.

# Results
Exporting Results: Save the results of your predictions to a CSV file for further analysis.
