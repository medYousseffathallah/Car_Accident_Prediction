Car Accident Prediction System
🚗 Project Overview
This AI-powered system predicts the likelihood of traffic accidents based on environmental and temporal factors. Using historical crash data, it helps identify high-risk conditions for preventive measures.

🔍 Key Features
Predicts accident probability using multiple risk factors

Handles real-world messy data with missing values

Generates synthetic non-accident data for balanced training

Optimizes model parameters automatically

📊 Model Performance
The optimized Random Forest classifier achieved outstanding results:

AUC-ROC: 1.00 (perfect discrimination)

Accuracy: 95%

Precision/Recall:

Accident prediction: 99% precision, 92% recall

Non-accident prediction: 91% precision, 98% recall

🤖 AI Model Details
Model Architecture
Algorithm: Random Forest Classifier

Optimization: Grid Search CV with 3-fold cross-validation

Best Parameters:

max_depth: 7

min_samples_split: 5

n_estimators: 100

Key Features Used
Posted speed limit

Weather conditions

Lighting conditions

Road surface condition

Crash hour (time of day)

Day of week

Geographic coordinates (latitude/longitude)
