**IMDb Movie Profit Prediction using Regression**

*📌 Project Overview*

This project predicts the profitability of movies using metadata such as budget, duration, genre, IMDb score, and more. Instead of classifying outcomes, it uses regression techniques to estimate profit in millions of dollars, enabling better financial decisions in the film industry.

📊 Dataset: IMDb 5000 Movies Dataset

🎯 Goal: Predict Total_Profit_in_millions using numerical and encoded features

🧠 ML Task: Regression

🧰 Tools & Libraries Used
Python

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Visualization

Scikit-learn – Model building and evaluation

Plotly – Interactive charts (optional)

🔧 Data Preprocessing
Filled missing values using mean/mode strategies

Removed columns with excessive null values

Extracted key features:

main_genres from genres list

Total_Profit_in_millions = gross - budget

Label encoded: main_genres, language, director

Selected numeric features for modeling

📊 Exploratory Data Analysis
Key analyses performed:

Genre-wise average profit

Distribution of IMDb scores

Language frequency and influence on profits

Correlation heatmap for numeric features

Sample Insight: Action, Adventure, and Sci-Fi genres show consistently higher profits with larger budgets and IMDb scores.

🧠 Regression Models Used
Model	R² Score	RMSE
Linear Regression	0.64	Moderate
Random Forest Regressor ✅	0.79	Lower error

📈 Random Forest performed best, explaining ~79% of the variance in movie profits.

📈 Visualization Highlights
Scatter plot: Actual vs Predicted Profit

Bar chart: Feature importance (from Random Forest)

Correlation heatmap

Boxplot: Profit by main genre

✅ Key Insights
Higher budget, IMDB score, and gross are strong predictors of profit.

Director and main genre also play influential roles.

Movies in English generate higher profits on average, followed by Hindi and Spanish.

🧪 Evaluation Metrics
R² Score – Model fit quality

MAE / RMSE – Model prediction error

Feature importance – Explained by Random Forest

