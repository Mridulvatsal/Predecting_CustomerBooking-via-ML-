# ✈️ Predicting Customer Bookings Using Machine Learning
**Company:** British Airways  
**Role:** Data Analyst – Mridul Vatsal  
**Project Type:** Classification | SMOTE | ML Model Comparison | Business Insights  

---

## 📌 Objective
To predict whether a customer will complete a booking using travel-related and demographic data, and to generate actionable insights for marketing and operations teams.

---

## 📊 Dataset
- **Size:** 10,000 records
- **Features:** Age, Gender, Trip Type, Destination, Past Bookings
- **Target:** `booking_complete` (0 = No, 1 = Yes)

---

## 🔍 Workflow
1. **EDA** (Class imbalance, feature dominance)
2. **Feature Engineering** (age_group, frequent_traveler, trip_popularity)
3. **Preprocessing** (One-Hot Encoding, SMOTE)
4. **Modeling** (Random Forest, Logistic Regression, SVM, Gradient Boosting)
5. **Evaluation** (F1, Precision, Accuracy, Confusion Matrix)
6. **Segmentation** (PCA + KMeans)
7. **Deployment-ready prediction function**
8. **Report Generation**

---

## 📈 Results
| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Random Forest      | 87%      | 85%       | 80%    | 82%      |
| Gradient Boosting  | 68%      | 70%       | 56%    | 62%      |
| SVM                | 53%      | 50%       | 59%    | 54%      |
| Logistic Regression| 51%      | 49%       | 61%    | 54%      |

---

## 🧠 Insights
- RoundTrip trips have the highest booking conversion.
- Destinations like Tokyo and Paris show strong trends.
- Customer segments vary significantly by age and booking patterns.

---

## 📄 Files
- `notebook/`: Full ML notebook with EDA, SMOTE, Modeling
- `data/`: Cleaned dataset used
- `reports/`: Final PDF summary report

---

## 🚀 Future Work
- Hyperparameter tuning (GridSearchCV)
- Streamlit dashboard
- Booking time-trend analysis
