# Accident Detection System

## 1. Overview

The Accident Detection System is designed to identify accidents using video or CCTV footage. With road accidents being a global issue, this project explores how CCTV technology combined with Machine Learning can effectively detect accidents and enhance safety measures on roads.

## 2. Prerequisites

To run this project successfully, the following are recommended:
- **Python Version:** 3.6 or higher
- **Knowledge Requirements:** 
  - Basic Python scripting
  - Understanding of Machine Learning concepts

## 3. Getting Started

### Step 1: Clone the Repository
Clone this repository to your local machine using:
```bash
https://github.com/Aaryan33/Accident-Detection-System.git
```

## Step 2: Install Required Packages
Navigate to the project directory and install the necessary packages:
```
pip install -r requirements.txt
```

## Step 3: Run the Program 
Execute the ```accident-classification.ipynb``` Jupyter Notebook to create the ```model_weights.keras``` file.
After the model is created, run the ```main.py``` script:
```
python main.py
```

## 4. Components

```Dataset :```  https://www.kaggle.com/datasets/ckay16/accident-detection-from-cctv-footage 

```camera.py :``` Integrates with the camera to capture video, executing the detection.py on each frame and displaying the accident prediction percentage.

```detection.py :``` Loads the Accident Detection system using the model.json and model_weights.keras files to perform predictions.

```accident-classification.ipynb :```  A Jupyter Notebook that generates a model to classify the dataset, producing two key files: model.json and model_weights.keras

## 5. Future Scope

  -> Automatically send the Google Maps location to the nearest hospital upon detecting an accident.
    
  -> Hospitals can accept the request and dispatch an ambulance to the location.
    
  -> The ambulance driver can access the Google Maps link received via email to reach the location quickly.
  
## Technology Used

    -> Python

    -> TensorFlow

    -> Matplotlib

    -> NumPy

    -> Convolutional Neural Networks (CNN)
