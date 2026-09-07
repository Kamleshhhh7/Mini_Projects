# NovaGen

## About the Project

NovaGen is a supervised learning classification project I created while learning how different machine learning models can be used and compared for the same prediction problem.

The project uses health and lifestyle-related features to predict the target outcome in the dataset.

Instead of relying on a single model, I experimented with several classification algorithms, including ensemble learning methods, and compared their performance using different evaluation metrics.

## What I Practiced

- Loading and exploring a dataset using Pandas
- Separating features and target variables
- Train-test splitting
- Feature scaling
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Gradient Boosting
- Voting Classifier
- Ensemble Learning
- Making predictions
- Accuracy evaluation
- Recall evaluation
- Classification reports
- Comparing multiple models

## Project Workflow

NovaGen Dataset
       ↓
Separate Features and Target
       ↓
Train-Test Split
       ↓
Feature Scaling
       ↓
Train Multiple Classification Models
       ↓
Logistic Regression
       ↓
KNN
       ↓
Random Forest
       ↓
Gradient Boosting
       ↓
Voting Classifier
       ↓
Evaluate Models
       ↓
Compare Results
       ↓
Select Best Classifier

## Models Used

### Logistic Regression

Logistic Regression was used as a baseline classification model to establish an initial performance level.

### K-Nearest Neighbors

KNN was used to classify samples based on the similarity between their feature values and nearby data points.

### Random Forest

Random Forest was used as an ensemble learning approach that combines multiple decision trees to make predictions.

### Gradient Boosting

Gradient Boosting was used as another ensemble learning technique to understand how models can be built sequentially to improve predictions.

### Voting Classifier

The Voting Classifier combines multiple classification models and uses their predictions to produce a final result.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Recall
- Classification Report

Recall was given particular importance in this project because missing a positive or high-risk case can be more important than accuracy alone.

## Model Comparison

The results from the notebook were:

| Model | Recall |
|---|---:|
| Logistic Regression | 82.8% |
| KNN | 88.3% |
| Random Forest | 95.8% |
| Gradient Boosting | 94.9% |
| Voting Classifier | 93.07% |

Based on the recall values from the notebook, **Random Forest achieved the highest recall of 95.8%** among the tested models.

## Dataset

The project uses `novagen_dataset.csv`.

The dataset contains health and lifestyle-related features such as:

- Age
- BMI
- Blood Pressure
- Cholesterol
- Glucose Level
- Heart Rate
- Sleep Hours
- Exercise Hours
- Water Intake
- Stress Level
- Smoking
- Alcohol
- Diet
- Mental Health
- Physical Activity
- Medical History
- Allergies
- Diet Type
- Blood Group

The `Target` column is used as the prediction target.

## Files

- `novagen.ipynb` — Main Jupyter Notebook
- `novagen_dataset.csv` — Dataset used for the project
- `README.md` — Project documentation

## What I Learned

This project helped me understand how multiple machine learning classification models can be trained and compared on the same dataset.

I also learned about ensemble learning through Random Forest, Gradient Boosting, and Voting Classifier.

Comparing models using recall helped me understand that model selection should depend on the problem and the evaluation metric that matters most, rather than looking only at accuracy.

## Future Improvements

As I learn more about machine learning, I would like to:

- Experiment with hyperparameter tuning
- Explore additional classification algorithms
- Perform more detailed feature analysis
- Compare additional evaluation metrics
- Improve the model comparison process
- Explore better ways to handle and engineer the available features

---

**Project Type:** Mini Project  
**Category:** Supervised Learning — Classification  
**Domain:** Health & Lifestyle Data  
**Models:** Logistic Regression, KNN, Random Forest, Gradient Boosting, Voting Classifier  
**Status:** Learning Project