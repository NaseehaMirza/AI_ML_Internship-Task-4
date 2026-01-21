# AI_ML_Internship-Task-4
# Feature Encoding & Scaling

## Objective
The objective of this task is to prepare the dataset for machine learning by applying feature encoding techniques for categorical variables and scaling numerical features. This step ensures that all data is in numerical form and on a comparable scale for effective model training.

## Dataset Used
- Adult Income Dataset

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn

## Steps Performed
1. Loaded and inspected the Adult Income dataset.
2. Identified categorical and numerical features.
3. Applied Label Encoding to the target variable where an order exists.
4. Applied One-Hot Encoding to nominal categorical features.
5. Scaled numerical features using StandardScaler.
6. Compared feature values before and after scaling.
7. Saved the final preprocessed dataset.

## Encoding Techniques Used
- **Label Encoding:** Applied to the target variable (`income`) to convert class labels into numerical form.
- **One-Hot Encoding:** Applied to categorical features without any inherent order to avoid introducing bias.

## Scaling Technique Used
- **StandardScaler:** Used to standardize numerical features so that they have a mean of 0 and a standard deviation of 1.

## Why Encoding and Scaling Are Important
- Machine learning models require numerical input.
- Encoding converts categorical data into numerical format.
- Scaling ensures that features with larger values do not dominate the learning process.
- Improves performance of distance-based and gradient-based algorithms.

## Outcome
- All features are converted into numerical form.
- Numerical features are scaled to a common range.
- The dataset is fully prepared and ready for machine learning models.

## Files Included
- Original dataset
- Preprocessed dataset
- Jupyter Notebook with encoding and scaling steps

## Learning Outcome
Through this task, I gained hands-on experience in feature engineering techniques such as encoding and scaling, and understood their importance in building efficient machine learning models.
