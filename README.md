# Employee Attrition Prediction Model

Welcome to the **Employee Attrition Prediction Model** project repository. This project focuses on developing machine learning models to predict employee attrition using a dataset of employee-related features. Real-time data collected via Google Form enriches the models with current organizational data, enhancing their relevance and applicability.

## Project Overview

The project aims to identify employees at risk of leaving an organization using predictive modeling techniques. It utilizes a dataset comprising features such as number of projects, average monthly hours, job satisfaction level, and more. Various machine learning algorithms are implemented and compared to determine the most effective model for predicting attrition.

## Key Features

- **Machine Learning Algorithms**: Implemented algorithms include Random Forest, Support Vector Machines (SVM), Decision Tree, Logistic Regression, and AdaBoost.
- **Model Performance**: The tuned AdaBoost model demonstrated the highest accuracy, precision, recall, and F1 score among all models tested.
- **Real-time Data**: Data collected via Google Form provides real-time insights into employee attributes, enhancing the predictive power of the models.

## Acknowledgments

The project acknowledges the use of real-time data collected through Google Form, which enriches the predictive models with current organizational data. This real-time aspect ensures that the models can adapt to changing trends and behaviors within the organization.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/<your-username>/Employee-Attrition-Prediction.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Employee-Attrition-Prediction
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

- **Data Collection**: Use Google Form to collect real-time employee data and update the dataset periodically.
- **Model Training and Evaluation**: Explore different machine learning algorithms in Jupyter notebooks (`attrition_prediction_random_forest.ipynb`, `attrition_prediction_svm.ipynb`, etc.) to train and evaluate models.
- **Model Deployment**: Choose the best-performing model (e.g., AdaBoost) for predicting employee attrition in real-world scenarios.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
