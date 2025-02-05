# Polynomial Linear Regression Analysis

This project involves analyzing the relationship between temperature and atmospheric pressure using both Simple Linear Regression and Polynomial Regression models. The analysis is performed using Python and various libraries such as `pandas`, `numpy`, `matplotlib`, and `scikit-learn`.

## Project Structure

- `notebooks/PolynomialLinearRegressionAnalysis.ipynb`: Jupyter notebook containing the analysis and visualization of the data.
- `data/raw/data.csv`: Raw data file containing temperature and pressure values.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

## Installation

To install the required packages, run:

```bash
pip install -f requirements.txt
```

## Analysis Overview

1. **Data Loading and Preprocessing**:
   - Load the data from `data.csv`.
   - Extract the temperature and pressure columns.

2. **Model Training**:
   - Train a Simple Linear Regression model.
   - Train Polynomial Regression models of degrees 2, 3, and 4.

3. **Visualization**:
   - Visualize the results of the Simple Linear Regression model.
   - Visualize the results of the Polynomial Regression models.

4. **Prediction**:
   - Predict pressure values for temperatures 10, 50, and 90 using both models.
   - Compare the predicted values from both models.

5. **Observations**:
   - Discuss the performance of both models and determine which model performs better.

## Usage

To run the analysis, open the Jupyter notebook `notebooks/PolynomialLinearRegressionAnalysis.ipynb` and execute the cells.

## Results

- The Polynomial Regression model provides more accurate predictions compared to the Simple Linear Regression model.
- The Polynomial model captures the curvilinear relationship between temperature and pressure better than the linear model.

## Conclusion

The Polynomial Regression model is recommended for predicting atmospheric pressure based on temperature due to its better performance in capturing the data's behavior.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.