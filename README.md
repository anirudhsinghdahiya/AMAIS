# Automated Military Aircraft Identification System (AMAIS)

## Overview
AMAIS is a machine learning project designed to accurately identify and classify military aircraft from images. By using advanced Convolutional Neural Networks (CNNs), this system aims to significantly improve recognition capabilities for various defense and monitoring applications.

## Authors
- Tanmay Modi
- Anirudh Dahiya
- Atreya Rawat

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Performance Evaluation](#performance-evaluation)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
To set up the project environment, clone the repo and install the required packages:

```bash
git clone https://github.com/YourUsername/AMAIS.git
cd AMAIS
pip install -r requirements.txt
```
## Usage
Run the following command to execute the project:
python main.py

## Dataset
The dataset includes labeled images of military aircraft with bounding box annotations. Detailed information can be found on Kaggle: https://www.kaggle.com/datasets/nicolassilvanash/milair-dataset/data

## Model Architecture
EfficientNet B4, pre-trained on ImageNet and fine-tuned for military aircraft identification, serves as our model architecture.

## Performance Evaluation
The model's performance is evaluated based on precision, recall, and F1-score metrics.

## License
This project is released under the MIT License. 
