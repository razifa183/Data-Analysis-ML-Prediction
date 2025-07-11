# Data-Analysis-ML-Prediction
It demonstrates a complete end-to-end data science workflow using the classic tips.csv dataset from the Seaborn library. The focus is on exploratory data analysis (EDA), data preprocessing, outlier handling, and building multiple regression and classification models with performance evaluation.

📂 Dataset
The dataset contains information about restaurant bills, tips given, customer demographics, and other categorical features like day and time of visit.

🔍 Key Tasks Performed

🧹 Data Preprocessing
    Loaded the tips.csv dataset using pandas
    Handled missing values:
        Detected null values using .isnull().sum()
        Filled missing values using mean/median imputation
    Handled outliers using Z-score method (scipy.stats.zscore)
    Encoded categorical features using LabelEncoder
    
📊 Exploratory Data Analysis (EDA)
    Generated correlation matrix using .corr()
    Plotted heatmap using Seaborn to visualize feature relationships
    Visualized distribution of features using boxplots and histograms

🧠 Machine Learning Models
✅ Linear Regression
Predicted tip amount based on other features

    Evaluated using:
         Mean Absolute Error (MAE)
         Mean Squared Error (MSE)
         R² Score

🌳 Random Forest Regressor
Trained for regression prediction of tips
Compared performance with Linear Regression

🔁 Logistic Regression
Converted a numerical target into binary class (e.g., high_tip vs low_tip)
Evaluated classification performance using:
       Accuracy
       Confusion Matrix
       Precision, Recall, F1-Score

📈 Visualization

    Boxplots for outlier detection
    Heatmaps for correlation analysis
    Bar charts and countplots for categorical feature distribution
    Actual vs Predicted plots for regression models
