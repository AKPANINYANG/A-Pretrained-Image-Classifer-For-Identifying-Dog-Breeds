# Project Title: Dog Breed Identification with Pre-trained Image Classifier

## Overview
This project harnesses the power of a pre-trained image classifier to accurately identify dog breeds from images. It involves a Python script that accepts an image or a directory of images and outputs the predicted dog breed for each image. The classification is done using a pre-trained deep learning model.

## Key Features
- Utilizes a pre-trained deep learning model to classify dog breeds in images.
- Handles command-line arguments to specify the input image or directory.
- Displays the predicted dog breed for each image.
- Evaluates the accuracy of the classifier by comparing the predicted breed with the actual breed.

## Installation
1. Clone the repository:
```bash
git clone https://github.com/AKPANINYANG/A-Pretrained-Image-Classifer-For-Identifying-Dog-Breeds.git
```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Navigate to the project directory:
```bash
cd your-repository
```
2. Run the script with the following command:
```bash
python check_images.py --dir <path-to-images-directory>
```
Replace `<path-to-images-directory>` with the path to the directory containing the images you want to classify. If no directory is specified, the script will use the default directory "pet_images/".

The script will then display the predicted dog breed for each image in the directory.

## Results
The script will output the accuracy of the classifier, including the percentage of correctly classified images, the percentage of correctly classified dog images, the percentage of correctly classified dog breeds, and the percentage of correctly classified non-dog images.

## License
This project is licensed under the MIT License.

## Acknowledgments
- The pre-trained deep learning model used in this project is provided by PyTorch.
- The dog breed labels used in this project are sourced from the Stanford Dogs Dataset.