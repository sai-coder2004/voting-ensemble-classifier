# voting-ensemble-classifier
🧾 Project Documentation: Voting Ensemble on Iris Dataset
📌 Project Title
Voting Ensemble Classifier on Iris Dataset

📚 Overview
This notebook demonstrates the use of Voting Ensemble Learning to improve classification accuracy by combining three different models:

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest

The dataset used is the classic Iris dataset from sklearn.datasets.

🛠️ Steps Implemented
Data Preparation

Loaded the Iris dataset and separated features and target.

Standardized the feature matrix using StandardScaler.

Model Initialization

Initialized three classifiers:

LogisticRegression

KNeighborsClassifier

RandomForestClassifier

Cross-Validation Accuracy

Each model was evaluated using 10-fold cross-validation.

Printed mean accuracies of individual models.

Voting Classifier

Combined all three classifiers using VotingClassifier.

Evaluated its performance on the same standardized dataset.

Observed the ensemble outperformed individual models slightly due to aggregated decision-making.

📈 Key Concepts Highlighted
Ensemble Learning: Technique to combine multiple models to produce better predictive performance.

Voting:

Hard Voting: Chooses the class label that has been predicted most frequently.

Soft Voting (not shown here): Averages class probabilities.

✅ Assumptions for Effective Ensemble
Base learners are independent.

Each model’s accuracy should ideally be ≥ 50%.
