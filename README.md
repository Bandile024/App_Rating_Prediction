# App Rating Prediction using Machine Learning

## Project Overview
The purpose of this project it to predict app rating using machine learning techniques.  
The focus was on improving model performance through feature engineering and data preprocessing.


## Objectives
- Predict app ratings based on available features  
- Handle categorical and numerical data  
- Improve model performance using feature engineering  
- Evaluate model accuracy using R² score  


## Dataset
The dataset contains information about mobile apps, including:
- App
- Category
- Content Rating
- Genres
- Reviews
- Installs
- Price
- Rating


## Data Preprocessing

### Handling Categorical Variables
- Used One-Hot Encoding (`pd.get_dummies()`)

### Feature Engineering
- Created:
  - `Installs_log` using log transformation
  - `Reviews_log`using log transformation
- This helped reduce skewness and improve model performance



## Model Used
- Linear Regression



## Model Performance

| Metric        | Score |
|--------------|------|
| Training R²  | 0.54 |
| Test R²      | 0.58 |

---

## Key Insights
- Log transformation of installs significantly improved model performance  
- Simpler models with strong features performed better than complex models  
- Higher installs generally lead to higher ratings  



## Conclusion
The model achieved good performance with an R² score of 0.58.  
Feature engineering played a key role in improving model accuracy.


## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib 


## Future Improvements 
- Try advanced models like Random Forest or XGBoost as the features available do not influence the app rating linearly  
- Hyperparameter tuning  


## Author
Bandile Ngwenya  
Data Science & AI Developer  