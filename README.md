# Leaf Disease Detection System

## Overview

Agriculture is vital to India, with tomato being a significant crop. The Leaf Disease Detection System uses technology to identify diseases in tomato leaves from uploaded images. This system aids farmers and plant enthusiasts by detecting diseases early, thereby safeguarding plants and improving agricultural productivity.

## Motivation

Nearly 65% of the Indian population depends on agriculture, making disease detection crucial for preserving crop health and yield. Tomatoes, being a staple vegetable, are susceptible to diseases like late blight, septoria leaf spot, and bacterial spot. Early detection through automated systems can mitigate yield losses significantly.

## Methodology
The Leaf Disease Detection System follows these key steps:

- **Image Acquisition**: Allows users to upload images of tomato leaves through an interface.
- **Image Pre-processing**: Enhances and restores uploaded images, converting them to grayscale and applying interpolation.
- **YOLO Model**: Uses the You Only Look Once (YOLO) algorithm to identify and localize disease regions by outputting bounding boxes around affected areas.
- **CNN Model**: Utilizes an optimized Convolutional Neural Network (CNN) to classify disease categories within the identified regions.
- **Classification and Recognition**: Matches identified regions against a dataset of tomato leaf diseases, providing outputs with disease names and recommended treatments (e.g., pesticides, fertilizers).

### Repository Content

- **dataset/**: Contains the dataset of images used for training and testing.
- **api/**: Includes the backend API for handling image uploads and processing.
- **frontend/**: Provides the frontend interface for users to interact with the system.
- **models/**: Holds trained models used for disease classification.
- **model1/**, **model2/**: Additional models or variations used in the project.
- **cnn_and_yolo_based_plant_disease_detection.ipynb**: Jupyter notebook containing code and explanations of the CNN and YOLO-based disease detection.
- **training/**: Scripts or notebooks used for model training and evaluation.

## Implementation Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your_username/Leaf-Disease-Detection-System.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Leaf-Disease-Detection-System
   ```

3. **Run the application**:

   - Set up the backend API (`api/`) and ensure dependencies are installed.
   - Launch the frontend (`frontend/`) to allow users to upload tomato leaf images.
   - Utilize the trained models (`models/`, `model1/`, `model2/`) for real-time disease detection and classification.

4. **Explore the Jupyter notebook**:

   - Review `cnn_and_yolo_based_plant_disease_detection.ipynb` for detailed insights into the CNN and YOLO-based approach used in the project.
