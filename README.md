# Predicting House Prices 🏡

In this repository, we delve deep into a dataset of housing properties to predict their sales prices. We employ a variety of data preprocessing, feature engineering, and machine learning techniques to achieve this.

![House Image](![Screenshot 2023-10-20 031658](https://github.com/beingrazaabbas/House-Prices-Prediction/assets/86911625/29cba744-c8bd-4570-972b-3dfb0757255d)
) 
*You can replace this with an actual image link for visualization.*

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)

## Dataset Overview
![Screenshot 2023-10-20 032449](https://github.com/beingrazaabbas/House-Prices-Prediction/assets/86911625/2b36dc36-2a2c-4e7d-940c-2f48618c74ff)

The dataset comprises numerous features related to housing properties, such as their physical attributes, location, and other essential characteristics. Our target variable is the `SalePrice`, which represents the price at which the house was sold.

## Data Preprocessing
![Screenshot 2023-10-20 031708](https://github.com/beingrazaabbas/House-Prices-Prediction/assets/86911625/0e80721f-854c-4cd4-9310-8c91a1515a97)

- **Handling Missing Data**: Identified columns with missing data and imputed them with median values (for numerical features) and mode or placeholders (for categorical features).
- **Feature Encoding**: Categorical variables underwent encoding. Ordinal variables were ordinal-encoded, while nominal variables were one-hot encoded.
- **Type Conversion**: Features were explicitly converted to their correct datatypes for consistency.

## Feature Engineering

- **Polynomial Features**: Squared certain features to capture potential non-linear relationships.
- **Log Transformations**: Applied on skewed features to achieve a more normal distribution, especially beneficial for linear models.
- **Binning**: The years when houses were built and remodeled were categorized into decade bins, capturing patterns related to different periods.

## Modeling
![Screenshot 2023-10-20 031721](https://github.com/beingrazaabbas/House-Prices-Prediction/assets/86911625/f3c50eeb-a411-421d-aa01-f481f7c4963c)

We explored a variety of machine learning models:

- Linear Regression, Ridge, Lasso
- Decision Tree, Random Forest
- Gradient Boosting, XGBoost, AdaBoost
- Ensemble Methods: Stacking and Blending

Performance metrics such as MAE, MSE, RMSE, and R^2 were employed to evaluate and compare model performance.

## Results

The models showcased varying levels of performance. Ensemble methods, especially Stacking, exhibited impressive results, indicating the power of combining multiple models. The results can be found in detail in the Jupyter Notebook within this repository.

## Conclusion

This project underscores the importance of comprehensive data preprocessing and feature engineering in enhancing model performance. The ensemble methods further demonstrate that combining diverse models can lead to improved predictions. Future work can explore deeper architectures like neural networks or more intricate feature engineering techniques.
