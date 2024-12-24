# DDoS Attack Detection in Software-Defined Networks using Machine Learning and Deep Learning Technologies

## Project Overview

This project aims to detect Distributed Denial-of-Service (DDoS) attacks in Software-Defined Networks (SDNs) using Machine Learning (ML) and Deep Learning (DL) technologies.  DDoS attacks pose a significant threat to network security, and traditional detection methods often fall short in dynamic SDN environments. This project explores the potential of advanced ML/DL models for accurate and timely DDoS detection.

## Dataset

The project utilizes a dataset containing network traffic features extracted from an SDN environment. The dataset includes labeled instances of normal traffic and DDoS attack traffic.

## Methodology

1. **Data Preprocessing:** The dataset is preprocessed to clean, normalize, and prepare it for model training.
2. **Feature Engineering:** Relevant features are selected or engineered to improve model performance.
3. **Model Development:** Several ML/DL models are implemented and trained, including:
    * **LSTM (Long Short-Term Memory)**
    * **Bi-LSTM (Bidirectional LSTM)**
    * **CNN (Convolutional Neural Network)**
    * **ANN (Artificial Neural Network)**
    * **SVM (Support Vector Machine)**
4. **Model Evaluation:** The trained models are evaluated using metrics such as accuracy, precision, recall, F1-score, and AUC (Area Under the ROC Curve).
5. **Comparison:** The performance of different models is compared to identify the most effective approach.

## Results

The project demonstrates the effectiveness of ML/DL models in detecting DDoS attacks in SDNs. The results show that the chosen models achieve high accuracy and provide a promising solution for enhancing network security.

## Usage

1. Clone the repository: `git clone <repository_url>`
2. Install the required libraries: `pip install -r requirements.txt`
3. Prepare the dataset: Ensure the dataset is in the correct format and location.
4. Run the model training script: `python train_model.py`
5. Evaluate the model: `python evaluate_model.py`

## Future Work

* Explore more advanced DL models.
* Optimize the model parameters for better performance.
* Implement real-time DDoS detection in an SDN environment.


## Contributing

Contributions to this project are welcome! If you find any bugs or have suggestions for improvement, please feel free to submit an issue or a pull request.
