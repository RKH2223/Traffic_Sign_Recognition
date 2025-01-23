# Traffic Sign Recognition

This repository contains the implementation of a **Traffic Sign Recognition** project. The objective is to develop a system that accurately identifies Indian traffic signs using a Convolutional Neural Network (CNN)-based approach and a custom dataset.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Traffic sign recognition plays a critical role in autonomous driving and road safety systems. This project uses deep learning techniques to classify traffic signs, focusing specifically on Indian road signs.

## Features
- Classification of various Indian traffic signs (e.g., stop signs, speed limits, cautionary signs).
- Utilizes a CNN-based architecture for high accuracy.
- Preprocessing pipeline for image normalization and augmentation.

## Dataset
A custom dataset of Indian traffic signs was created for this project. The dataset includes:
- Traffic signs across different categories (e.g., regulatory, warning, and informatory signs).
- Images preprocessed for resizing, normalization, and data augmentation.

## Model Architecture
The project uses a CNN-based model with the following layers:
- Convolutional layers for feature extraction.
- Pooling layers for dimensionality reduction.
- Fully connected layers for classification.
- Dropout layers to prevent overfitting.

## Installation
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/traffic-sign-recognition.git
   cd traffic-sign-recognition
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Preprocessing:** Prepare the dataset by running:
   ```bash
   python preprocess.py
   ```

2. **Training the Model:** Train the CNN model:
   ```bash
   python train.py --epochs 20
   ```

3. **Testing the Model:** Test the trained model on a sample image:
   ```bash
   python test.py --image data/sample_traffic_sign.jpg
   ```

4. **Visualizing Results:** Plot training accuracy and loss:
   ```bash
   python visualize.py
   ```

## Results
- Achieved high classification accuracy on the test dataset.
- Model performance metrics:
  - Accuracy: XX%
  - Precision: XX%
  - Recall: XX%
- Confusion matrix and classification report are available in the `results/` folder.

## Future Work
- Expand the dataset to include more diverse and challenging traffic signs.
- Optimize the model for real-time recognition on edge devices.
- Integrate with a real-time object detection framework (e.g., YOLO or SSD).

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
For any questions or suggestions, feel free to reach out! You can contact me at [ravikanani2003@gmail.com](mailto:ravikanani2003@gmail.com) or connect with me on [LinkedIn](https://www.linkedin.com/in/ravi-kanani/).

