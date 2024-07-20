# Pneumonia Detection using Neural Networks

## Overview
This project aims to detect pneumonia using various neural network architectures, including toy neural networks, Convolutional Neural Networks (CNNs), and Transfer Learning with pre-trained models. The dataset consists of chest X-ray images, and the objective is to distinguish between pneumonia-afflicted and healthy cases.

## Data Collection and Preparation
1. **Data Collection:**
   - Chest X-ray images and metadata are downloaded from specified URLs.
   - The data is organized into training, validation, and test sets.

2. **Data Preprocessing:**
   - Images are resized and augmented using techniques such as rotation, shearing, scaling, and flipping.
   - Metadata is used to manage data splits and labels.

## Model Building

1. **Toy Neural Network:**
   - A basic neural network with dense layers, ReLU activation functions, and dropout for regularization is created.

2. **Convolutional Neural Network (CNN):**
   - A CNN model is designed with convolutional layers, activation functions, pooling layers, and dropout to analyze and classify chest X-ray images.

3. **Transfer Learning:**
   - Pre-trained models such as VGG16, VGG19, ResNet50, and DenseNet121 are fine-tuned for pneumonia detection.
   - The models include additional dense layers and dropout for classification.

## Model Training and Evaluation

1. **Training:**
   - Models are trained using the prepared training data with validation on a separate dataset.
   - The best-performing model is selected based on validation accuracy.

2. **Evaluation:**
   - The final model is evaluated on the test set.
   - Performance metrics such as accuracy, precision, recall, and F1-score are calculated.
   - A confusion matrix is generated to visualize classification results.

## Internship Experience
This project was part of the "Artificial Intelligence in Healthcare" internship by InfiLabs, where I gained practical experience in data cleaning, machine learning, AI, and neural networks over a two-month period.

## Installation and Setup
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/pneumonia-detection.git
    ```

2. **Install Required Libraries:**
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras imgaug
    ```

3. **Download Data:**
    - The data files will be automatically downloaded when you run the project code.

4. **Run the Code:**
    - Execute the project scripts to start data preprocessing, model building, training, and evaluation.

## Contribution
This project was developed as part of an internship and collaborative effort. Contributions include designing neural network architectures, training models, and evaluating performance.


## Contact
- **Name:** Sanjeevi Kumar K V
- **Email:** sanjeevikumarkv@gmail.com
- **GitHub:** [sanjeevikumar-kv](https://github.com/sanjeevikumar-kv)
- **LinkedIn:** [Sanjeevi Kumar K V](https://linkedin.com/in/sanjeevi-kumar-k-v-a63a35221)
- **Google Developer Profile:** [Sanjeevi Kumar K V](https://g.dev/sanjeevikumarkv)

## Acknowledgements
- This project was completed as part of the "Artificial Intelligence in Healthcare" internship by InfiLabs.
- Special thanks to InfiLabs for providing the opportunity to work on this project and gain valuable skills.


[pneumonia-detection.pdf](https://github.com/sanjeevikumar-kv/Pneumonia_Detection/files/13266758/pneumonia-detection.pdf)
