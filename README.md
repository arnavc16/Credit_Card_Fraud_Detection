# Credit Card Fraud Detection using Behavioral Biometrics

## Project Overview
This project integrates behavioral biometrics with machine learning models to enhance the detection of credit card fraud. By incorporating user interaction patterns such as keystroke dynamics, mouse movements, and scroll patterns, the model aims to improve the accuracy and reliability of traditional fraud detection systems.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Modeling Approach](#modeling-approach)
4. [Results and Analysis](#results-and-analysis)
5. [Installation](#installation)
6. [Usage](#usage)
7. [References](#references)
8. [License](#license)

## Dataset
The dataset used in this project is synthetically generated using AI techniques and includes both transactional data and behavioral biometrics. It simulates real-world financial transactions and user interactions.

- **File:** `data/credit_card_fraud_detection_data.csv`

## Modeling Approach
1. **Data Preprocessing:** 
   - Handling numerical and categorical data, scaling, and encoding.
   - Feature engineering to extract key interaction metrics.

2. **Model Training:**
   - The RandomForest classifier was used due to its robustness against overfitting and ability to handle both categorical and numerical data.

3. **Evaluation:**
   - The model was evaluated using accuracy, precision, recall, and F1-score.

## Results and Analysis
- **Accuracy:** 71%
- **Precision:** 80% for fraudulent transactions.
- **Recall:** 57% for fraudulent transactions.
- **F1-Score:** 67%

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/arnavc16/credit_card_fraud_detection.git
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open the Jupyter notebook `src/credit_card_fraud_detection.ipynb` and run the cells sequentially.
2. View the results and visualizations for the fraud detection model.

## References
- Subash, A., & Song, I. (2021). Real-Time Behavioral Biometric Information Security System for Assessment Fraud Detection. IEEE International Conference on Computing.
- Khan, H. U., Malik, M. Z., Nazir, S., & Khan, F. (2023). Utilizing Biometric System for Enhancing Cyber Security in Banking Sector: A Systematic Analysis. IEEE Access.
- Awad, A. (2017). Collective Framework for Fraud Detection Using Behavioral Biometrics. Information Security Practices.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
