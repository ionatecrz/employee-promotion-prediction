
# Employee Promotion Prediction

## Project Description

This project aims to predict whether an employee will be promoted based on personal, professional, and performance-related attributes. The developed solution integrates advanced Machine Learning techniques and addresses the challenges of imbalanced data to support decision-making in promotion processes.

## Repository Contents

- **`data/`**: Contains the datasets used for analysis.
- **`notebooks/`**: Includes the notebook `employee_prediction.ipynb`, which contains preprocessing, modeling, and evaluation.
- **`final_classifier.txt`**: The saved LightGBM model, stored using joblib.
- **`requirements.txt`**: Lists the dependencies required to run the project.
- **`README.md`**: This file, providing information about the project and usage instructions.

## Requirements

- **Python**: >= 3.7
- Key Libraries:
  - Data Manipulation: `numpy`, `pandas`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Modeling: `scikit-learn`, `xgboost`, `lightgbm`, `imbalanced-learn`
  - Others: `joblib`, `statsmodels`

## Usage Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ionatecrz/employee-promotion-prediction.git
   cd employee-promotion-prediction
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the notebook**:
   - Open the `notebooks/employee_prediction.ipynb` file using Jupyter Notebook or Jupyter Lab.
   - Execute the cells sequentially to perform the analysis and evaluate the models.

## Key Results

- The **LightGBM** model excelled in addressing class imbalance and accurately identifying employees eligible for promotion.

- Top influential features include `avg_training_score`, `age`, `previous_year_rating`, and `length_of_service`.

- Macro and average metrics were used to evaluate model performance across both classes (promoted and non-promoted).

## Business Benefits

- **Data-Driven Decision-Making**: Reduces biases and provides an objective approach.
- **Uncover Hidden Talent**: Highlights employees with leadership potential.
- **Optimize Resources**: Improves organizational development programs.
- **Fair Processes**: Identifies potential inequalities in promotions.

## Author

- **Author Name**: Íñigo de Oñate Cruz
- **Contact**: [LinkedIn](https://www.linkedin.com/in/%C3%AD%C3%B1igo-de-o%C3%B1ate-cruz-855b55263/)

## License

This project is licensed under the [MIT License](LICENSE), allowing use, modification, and distribution.
