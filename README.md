#   Car Insurance Claim Prediction using Naive Bayes Algorithm

In this repository, I implemented the Naive Bayes classifier to predict whether a customer will file a car insurance claim based on various features such as credit score, annual mileage, vehicle age, and more.

 About the Dataset
The dataset used for this project contains various attributes related to car insurance claims, including both numerical and categorical features. Each row represents a policyholder, and the target variable indicates whether they have made a claim (1) or not (0).

🔹 Key Features in the Dataset:

✅ CREDIT_SCORE – Creditworthiness of the customer

✅ ANNUAL_MILEAGE – Total miles driven per year

✅ VEHICLE_AGE – Age of the insured vehicle

✅ DRIVING_EXPERIENCE – Number of years the customer has been driving

✅ INCOME_GROUP – Income category of the policyholder

✅ PREVIOUS_ACCIDENTS – Number of past accidents

✅ TARGET VARIABLE: CLAIM_STATUS (1 = Made a claim, 0 = No claim)

The goal is to predict whether a customer will file a claim based on their characteristics.


##  **About Naive Bayes Algorithm**  
Naive Bayes is a probabilistic classification algorithm based on Bayes’ theorem, which calculates the probability of an event occurring based on prior knowledge of related conditions.
\[
P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
\]
this algorithm-
✔️ Works well with categorical & numerical data

✔️ Assumes independence between features, making it computationally efficient

✔️ Performs well even on small datasets

✔️ Suitable for binary classification problems like claim prediction

For this project, I used Gaussian Naive Bayes, which assumes that numerical features follow a normal distribution.

This model assumes:  
✅ **Feature Independence** – Each feature contributes independently to the final outcome.

✅ **Fast & Efficient** – Works well with large datasets.  

✅ **Handles Categorical & Numerical Data** – Especially useful for classification problems.

✅ **Gaussian Naïve Bayes (GNB)** – Assumes a normal distribution for numerical features.  

---
 Implementation Steps
 
🔹 Data Preprocessing

✔️ Load the dataset using Pandas.

✔️ Handle missing values using mode imputation.

✔️ Encode categorical features using LabelEncoder.

✔️ Drop irrelevant columns (e.g., ID).

✔️ Scale numerical features using StandardScaler.

🔹 Model Training & Prediction

✔️ Split dataset into training and testing sets.

✔️ Train a Gaussian Naïve Bayes model.

✔️ Make predictions on the test set.

🔹 Model Evaluation

✔️ Accuracy Score – Measures overall correctness of predictions.

✔️ Confusion Matrix – Displays classification results.

✔️ Classification Report – Provides precision, recall, and F1-score for each class.




