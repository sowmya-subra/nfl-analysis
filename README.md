# **NFL Fourth-Down Decision Analysis**

## **Overview**
Welcome to the repository for the NFL Fourth-Down Decision Analysis project! This research explores decision-making strategies in NFL fourth-down plays using advanced machine learning techniques. By analyzing data from the 2021 to 2023 NFL seasons, this study aims to provide actionable insights into the factors that influence the success of fourth-down conversions, helping teams optimize their strategies during critical game moments.

### **Project Summary**
The objective of this project is to understand and predict NFL fourth-down play decisions, specifically whether to attempt a conversion, punt, or kick a field goal. Utilizing a comprehensive dataset and sophisticated analytical models, we identify key factors influencing these decisions and evaluate their impact on game outcomes.

### **Key Components**
**Data Source:** NFLverse GitHub repository, covering every play from NFL games from 1999 to the present, with a focus on the 2021-2023 seasons.

**Analysis Methods:** Logistic regression, decision tree classifier, and support vector machine models.

**Key Variables:** Distance to first down, play type, game clock time, score differential, and more.

## **Methodology**

### **Data Preparation:**
- Data was cleaned and normalized using Python's pandas library.
- Missing values were imputed with historical averages for weather conditions.
- Key features were engineered, including a derived variable indicating whether a timeout was called immediately before the play.

### **Modeling:**
- Logistic Regression, Decision Tree, and Support Vector Machine models were employed.
- Hyperparameters were optimized using Grid Search.
- Models were evaluated based on accuracy, with a focus on mitigating overfitting.

## **Feature Importance:**
- Feature importance analysis identified "drive_play_count" as the most influential predictor, contrary to initial expectations.

## **Results:**
- The logistic regression model outperformed other models with an accuracy of 84.8% on validation data and 83.5% on unseen test data.
- The ROC curve analysis yielded an AUC of 0.90, indicating excellent model performance.
- Key insights include the significant impact of game clock time and score differential on fourth-down decisions.

## **Findings:**
The research challenges traditional conservative play-calling norms, highlighting the importance of variables such as game context and offensive momentum. These findings offer valuable guidance for optimizing fourth-down strategies, potentially enhancing team performance and game management.

## **Files in this Repository**:
data/: Contains the cleaned and processed datasets used for analysis.

notebooks/: Jupyter notebooks detailing the data preprocessing, model training, and evaluation processes.

documents/: Contains final presentation presented in class, docx file of detailed report

README.md: This file.

## **Acknowledgements:**
Special thanks to the NFLverse GitHub repository for providing the dataset used in this research.
