# ⭐AGRO-CARE: Plant Disease Detection System

Plant disease detection is crucial for every farmer, so we have created a plant disease detection system using deep learning. We use a Convolutional Neural Network (CNN) for classifying leaf images into 39 different categories. The CNN model is built using the PyTorch framework. For training, we utilize the Plant Village dataset. You can find the dataset link in the Blog section of our repository. AGRO-CARE is an advanced plant disease detection system with a user-friendly interface. It allows users to upload pictures of diseased leaves, detects the disease, provides information on curing the disease, suggests supplements, and offers an option to buy the supplements.

## Features

- **Disease Detection**: Upload a picture of diseased leaves and the system will identify the disease.
- **Cure Information**: Get detailed information on how to cure the detected disease.
- **Supplement Suggestions**: Receive suggestions for supplements that can help in curing the disease.
- **E-commerce Integration**: Purchase the recommended supplements directly through the platform.

## Testing Images

- If you do not have leaf images, you can use test images located in the `test_images` folder.
- Each image has its disease name, so you can verify if the model is working correctly.

## Installation

1. Clone the repository:

    git clone https://github.com/mahima16yadav/agro-care.git
   
    cd agro-care


3. Ensure you have Python and the required dependencies installed. You can install the dependencies using:

    pip install -r requirements.txt

4. Download the pre-trained model and place it in the specified directory.

## Usage

Run the application using:

python main.py
