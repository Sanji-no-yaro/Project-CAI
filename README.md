# COVID-19 Detection System (Code name: # Project-CAI)


**Course**: Deployment of AI Solutions (AISC2013)  
**Group**: 3  
**Date**: July 12, 2024

## Group Members

| Name             | Student Id |
|------------------|------------|
| Ajit Kulkarni    | 500223502  |
| Jasdeep Kaur     | 500224259  |
| Ashtami Vijayan  | 500224260  |
| Anjali Bhardwaj  | 500223877  |

## Project Overview

The aim of this research is to develop a robust Deep Neural Network model capable of accurately detecting COVID-19 from lung images. The necessity for such a model arises from the urgent need for early and precise diagnosis of COVID-19, which is crucial for timely patient isolation, treatment initiation, and optimal resource utilization.

## Motivation

Early detection of COVID-19 can significantly reduce the virus's transmission rate within hospitals and communities, alleviating the strain on healthcare systems, especially in resource-limited areas. By enabling prompt interventions and appropriate allocation of medical resources, this research seeks to enhance patient outcomes and public health responses amid the ongoing global pandemic.

## Method

The identification of COVID-19 from chest X-ray or CT scan images will be carried out using Convolutional Neural Networks (CNNs). CNNs excel at extracting complex patterns and spatial hierarchies from images, making them particularly effective in distinguishing COVID-19 from other lung diseases.

The CNN component will utilize multiple layers of convolutional filters to capture low-level features such as edges and textures, as well as high-level features like shapes and disease-specific indicators. These extracted features will then be processed by an Artificial Neural Network (ANN), which will classify the presence of COVID-19 based on the identified patterns and characteristics. This combined approach leverages the strengths of both CNNs and ANNs to enhance model accuracy and reliability, aiding physicians in diagnosis and improving patient outcomes.

## Experiment

This study aims to evaluate the effectiveness of various CNN architectures, including ResNet, VGG, and Inception, in detecting COVID-19 from lung images. Through comprehensive hyperparameter optimization of learning rate, batch size, and dropout rate, we aim to enhance performance metrics such as accuracy, precision, recall, and F1-score. The primary objective of the evaluation is to determine how well CNNs can utilize visual cues from medical images to differentiate COVID-19 from other lung diseases. By identifying the optimal architecture and parameter combinations for COVID-19 diagnosis, this project seeks to provide healthcare practitioners with a reliable tool for rapid patient management and resource allocation.

## Tasks

- **Task 1: Dataset Review and Preprocessing**  
  Assigned to: Ashtami  
  This task involves collecting, reviewing, and preprocessing the datasets to ensure they are suitable for model training. This includes normalization, augmentation, and splitting the data into training, validation, and test sets.

- **Task 2: CNN Architecture Design and Implementation**  
  Assigned to: Anjali  
  This task focuses on designing and implementing various CNN architectures, such as ResNet, VGG, and Inception, tailored for COVID-19 detection from lung images.

- **Task 3: Model Training, Hyperparameter Tuning, and UI Integration**  
  Assigned to: Ajit  
  This involves training the designed CNN models and performing hyperparameter tuning to optimize performance metrics like accuracy, precision, recall, and F1-score. Additionally, Ajit will develop and integrate the user interface using Flask, allowing healthcare professionals to upload lung images and receive real-time predictions.

- **Task 4: Model Evaluation and Analysis, Future Scope and Applications**  
  Assigned to: Jasdeep  
  This task includes evaluating the trained models, analyzing their performance, and selecting the best model based on the evaluation metrics.

(Note: Presentation Task will be divided and noted on the GitHub main branch for Professor review.)

## Dataset

- **COVID Dataset**: Contains 5000 images, with 1800 non-COVID, 1700 COVID, and the remaining with other diseases.
- **COVID-19 Radiography Dataset**: Includes 11,956 COVID-19 images, 11,263 non-COVID infections (viral or bacterial pneumonia), and 10,701 normal images.
- **SIIM COVID-19 Dataset**: Comprises 7597 images.

## UI Integration

The integration of a user interface (UI) with the AI model will be done using Flask. This UI will allow healthcare professionals to upload lung images and receive real-time predictions on the likelihood of COVID-19 infection. The key features of the UI include:

- **Image Upload**: Users can upload chest X-ray or CT scan images through a simple interface.
- **Real-Time Prediction**: The model processes the uploaded images and provides immediate predictions on the presence of COVID-19.
- **Result Display**: The UI displays the prediction results along with confidence scores, helping physicians make informed decisions.
- **User-Friendly Design**: The interface is designed to be intuitive and accessible, ensuring that healthcare practitioners can use it with minimal training.

## References

- COVID-19 Dataset on GitHub
- COVID-19 Radiography Database on Kaggle
- SIIM COVID-19 Dataset on Kaggle
