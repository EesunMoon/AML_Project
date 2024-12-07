# Analyzing Fitness Patterns & Building Predictive Models using Gym Members Exercise Dataset

## Overview

This project focuses on analyzing gym members’ fitness patterns and building predictive models for personalized exercise recommendations. The project uses machine learning and data analysis techniques to derive insights from the provided dataset.

### Project Files
1. **`gym_members_exercise_tracking.csv`**
   - Dataset file.
2. **`Final_Report.pdf`**
   - Comprehensive project documentation including objectives, methodology, analysis, and results.
3. **`Project_Part3_Deliverable.ipynb`**
   - Jupyter Notebook containing the entire code for the project, including:
     - Data preprocessing
     - Machine learning models (regression, clustering, recommender systems)
     - Progression analysis
     - Visualizations and explanations for each step.
4. **`README.md`**
   - This file, providing setup and usage instructions.

### Prerequisites
Ensure the following are installed on your system:
1. Python (version 3.7 or above)
2. **Jupyter Notebook** or **VS Code** with the Jupyter extension
3. Required Python libraries:
   - Install the dependencies using:
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
     ```

### How to Run the Code
1. Open **Visual Studio Code** or any text editor supporting Jupyter notebooks.
2. Open `Project_Part3_Deliverable.ipynb` in VS Code.
3. Ensure the Python interpreter is set correctly by selecting your virtual environment (if used) or the default Python installation.
4. Run the notebook:
   - Click **"Run All"** or run individual cells to execute the analysis.

---

## Dataset

The dataset comprises **973 records** with **15 features** spanning demographic, physiological, and workout data. It is sourced from Kaggle.

### Features:
- **Demographics**: Age, Gender, Weight, Height
- **Physiological Metrics**: Max BPM, Avg BPM, BMI
- **Workout Metrics**: Workout Session Duration, Workout Frequency, Calories Burned (target)

The dataset is complete with no missing values.

---

## Project Goals
1. **Identify Key Factors**: Analyze the most significant factors affecting fitness outcomes.
2. **Personalized Recommendations**: Develop predictive models for tailored workout suggestions.
3. **Progression Analysis**: Uncover patterns in workout adherence and improvement.

---

## Methodology
1. **Exploratory Data Analysis**:
   - Correlation analysis.
   - Bivariate analysis by demographic subgroups.
   - Outlier detection and scaling.
2. **Machine Learning Models**:
   - Regression models: Linear, Ridge, Lasso, Random Forest, Neural Networks.
   - Clustering: PCA, DBSCAN, and K-Means.
   - Recommender System: Neural Collaborative Filtering.
3. **Progression Analysis**:
   - Classification of experience levels using Random Forest and Logistic Regression.
   - Group analysis by workout frequency, session duration, water intake, and calorie burn.
4. **Hyperparameter Tuning**:
   - Optimized parameters like `n_estimators`, `min_samples_split`, and `max_depth` for Random Forest models.

---

## Key Findings
- **Top Influential Factors**:
  - Session Duration, Avg BPM, Gender, Age, and Weight significantly affect calories burned.
- **Recommender System**:
  - Achieved a MAP@2 score of **0.535** using Neural Collaborative Filtering.
- **Progression Insights**:
  - Users at higher experience levels burn more calories, work out longer, and hydrate better.
  - Beginners benefit from additional incentives to achieve higher experience levels.

---

### Technologies Used
- **Languages**: Python
- **Libraries**: Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn, TensorFlow

### Machine Learning Techniques:
- **Regression**: Linear, Ridge, Lasso, Random Forest, Neural Networks
- **Clustering**: DBSCAN, K-Means
- **Recommender System**: Neural Collaborative Filtering

---

### Results
1. **Calories Burn Prediction**:
   - Random Forest and Neural Networks achieved high R² scores (~0.65) with minimal error.
2. **Workout Recommendations**:
   - Suggestion-based model recommends workout types and predicts calorie burn with session duration.
3. **Progression Analysis**:
   - Significant differences observed across experience levels in adherence metrics and fitness outcomes.
---

### Future Enhancements
- Expanding the dataset to improve the recommender system’s accuracy.
- Incorporating additional features for deeper insights into fitness behaviors.

---

## Contributors

**Team 27**:
- tc3117
- em3907
- ap4613
- tz2634
- jy3344
