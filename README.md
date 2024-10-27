# HEART_DISEASE_DETECT

![Heart Disease Detection](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-green)
![Status](https://img.shields.io/badge/Status-Completed-blue)

## Project Overview
**HEART_DISEASE_DETECT** is a machine learning project that aims to predict the likelihood of heart disease in individuals based on medical data. This project utilizes various machine learning algorithms to analyze the dataset and compare model performances. After experimenting with multiple algorithms, **Logistic Regression** was chosen as the final model due to its superior accuracy.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Algorithms Analyzed](#algorithms-analyzed)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset used in this project consists of medical and demographic information that includes features such as:
- Age
- Gender
- Blood Pressure
- Cholesterol Levels
- Resting Heart Rate
- ECG Results
- Maximum Heart Rate
- Exercise-Induced Angina
- Other cardiovascular indicators
  ![image](https://github.com/user-attachments/assets/cfd999a9-0c48-471a-b984-c6cedb8ad298)


This data was used to train and test the machine learning models, enabling the system to identify patterns associated with heart disease.

## Algorithms Analyzed
To determine the most effective algorithm for heart disease prediction, we tested several machine learning models:
1. **K-Nearest Neighbors (KNN)**: A simple classification algorithm based on the distance between data points.
2. **Decision Trees**: A tree-like model used for decision making and classification tasks.
3. **Logistic Regression**: A statistical model suitable for binary classification problems, which performed best in this project.
4. **Support Vector Machines (SVM)**: A powerful classification model that aims to find a hyperplane separating different classes.

After analyzing the accuracy and effectiveness of each algorithm, **Logistic Regression** was selected as the primary model due to its high accuracy and interpretability.

## Installation

To set up this project, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/HEART_DISEASE_DETECT.git
    cd HEART_DISEASE_DETECT
    ```

2. **Install Dependencies**
    Ensure you have Python installed, then install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
    Required libraries include:
    - `pandas`
    - `numpy`
    - `scikit-learn`
    - `matplotlib`
    - `seaborn`

3. **Prepare the Dataset**
    Place the dataset file in the project directory. If using a public dataset, link it here or provide instructions on acquiring the dataset.

## Usage

To run the project, follow these steps:

1. **Data Preprocessing**
    Clean and preprocess the data to make it suitable for machine learning. Run the data preprocessing script:
    ```bash
    python preprocess_data.py
    ```

2. **Train the Model**
    Train the Logistic Regression model on the preprocessed data:
    ```bash
    python train_model.py
    ```

3. **Make Predictions**
    Once the model is trained, use it to make predictions on new data:
    ```bash
    python predict.py --input sample_data.csv
    ```

4. **Evaluate Model Performance**
    Evaluate the trained model’s performance on a test set:
    ```bash
    python evaluate_model.py
    ```

## Model Performance
After evaluating each model on accuracy and generalization capabilities, the following results were obtained:

| Algorithm              | Accuracy  |
|------------------------|-----------|
| K-Nearest Neighbors    | 68%       |
| Decision Trees         | 73%       |
| Logistic Regression    | **Highest Accuracy - 84%** |
| Support Vector Machines| 75%       |

With Logistic Regression achieving the highest accuracy, it was selected as the final model for heart disease prediction.

## Results
The **HEART_DISEASE_DETECT** model, powered by Logistic Regression, achieved an accuracy of **YY%** on the test set. The model effectively identified individuals at higher risk for heart disease based on their medical and demographic information.

### Key Insights
- Logistic Regression provided the highest accuracy among the models tested.
- The model can assist healthcare providers by identifying patients at risk, allowing for timely intervention.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
