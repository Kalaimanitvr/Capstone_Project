# ⚽ Comprehensive Football Analysis: Insights & Strategic Recommendations ⚽
##      Tools used: Python | SQL | Tableau |  

## 🌐 Quick Access Links
Access the key files for this project:
- 📓 **[Jupyter Notebook](./project_final.ipynb)**: Core data analysis and machine learning workflows.
- 📑 **[Data Dictionary](./data%20dictionary_football.pdf)**: Detailed column descriptions of the dataset.
- 🛠️ **[Preprocessing Guide](./Data%20Preprocessing_KalaimaniMuthu.pdf)**: Data cleaning and preparation steps.
- 📊 **[Presentation Slides](./Kalaimani_project_cap111.pdf)**: Summary of insights and strategic recommendations.
- 🌐 **[Tableau Dashboard](https://public.tableau.com/views/Kalaimani_Muthu_dashboard/Home?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link )**.

---

## 📜 Project Introduction
Football is more than just a game; it's a world driven by data. This project aims to use **data analysis and machine learning** to uncover trends, predict outcomes, and provide actionable insights for football teams, managers, and fans. By analyzing player performance, team strategies, and attendance patterns, this project answers critical business questions while showcasing the power of data.

As a **data analyst**, my goal was to:
- **Transform raw data into meaningful insights**.
- **Use advanced visualization techniques to tell compelling stories**.
- **Build predictive models** to assist decision-making in the football domain.

---

## 🎯 Objectives
### Primary Goals
1. **Performance Analysis**:
   - Identify top-performing players and track trends across seasons and positions.
   - Predict player performance and match outcomes using statistical models.

2. **Player Market Value**:
   - Analyze factors influencing player market value (e.g., goals, assists, positions).
   - Build predictive models to estimate player value based on key features.

3. **Team and Venue Analysis**:
   - Compare strategies in home vs. away games.
   - Evaluate the impact of managers and venue performance on team outcomes.

4. **Attendance Trends**:
   - Study patterns in match attendance over seasons.
   - Categorize matches into high, medium, and low attendance using machine learning.

5. **Referee and Event Analysis**:
   - Assess referee behavior and its influence on match outcomes.
   - Analyze common game events like fouls, yellow/red cards, and substitutions.

6. **Player Attributes and Demographics**:
   - Explore relationships between player attributes and performance.
   - Segment players using clustering techniques.

---

## 🛠️ Methodology
### Data Collection and Preprocessing
- **Dataset**: Merged and cleaned multiple football-related datasets to create a unified structure.
- **Steps Taken**:
  - Missing value treatment.
  - Feature engineering (e.g., calculating player goals per minute).
  - Data merging using shared keys (game IDs, player IDs).
- **Tools**: Python (pandas, numpy), Tableau, and Excel.
- Generated a [Data Dictionary](./data%20dictionary_football.pdf) to document the dataset structure.

---

### Machine Learning and Analysis Process
1. **Exploratory Data Analysis (EDA)**:
   - Visualized key metrics like player performance, attendance trends, and team strategies.
   - Used Tableau to create interactive dashboards.

2. **Modeling Techniques**:
   - **Logistic Regression**: Predicted:
     - Starting lineups based on goals scored.
     - Likelihood of a player receiving a yellow card.
   - **Linear Regression**: Estimated player market value using:
     - Simple linear regression (scoring frequency as a predictor).
     - Multiple linear regression (goals, assists, height, and other features).
   - **K-Nearest Neighbors (KNN)**:
     - Categorized matches into attendance groups (high, medium, low).
   - **K-Means Clustering**:
     - Grouped players based on demographics (height, age) and performance metrics.

3. **Statistical Analysis**:
   - Hypothesis testing to identify differences in goals scored across venues.
   - Probability calculations for player scoring likelihood based on assists.

4. **Evaluation Metrics**:
   - AUC, precision, recall, F1-score for classification models.
   - R², MSE, and RMSE for regression models.

---

## 📈 Key Insights and Findings
### ⚽ Player Performance
- **Top Players**:
  - Identified top 5 goal scorers and assist providers for the latest season.
  - Goalkeepers average 89.6 minutes/game, while attackers average the least at 59.8 minutes.
- **Predictive Insights**:
  - Starting lineup prediction achieved an **AUC of 0.63**.

### 💰 Market Value
- Right midfielders have the highest average market value (€4.14M), while left wingers have the lowest (€0.4M).
- Market value prediction models showed:
  - Simple regression R² = 0.002 (low explanatory power).
  - Multiple regression R² = 0.044 (slightly better, but still low).

### 🏟️ Attendance Trends
- **Top Venue**: Signal Iduna Park recorded the highest average attendance (73,740 fans).
- Matches were categorized into attendance groups using KNN (36.1% accuracy).

### ⚖️ Referee Behavior
- Referee Felix Zwayer issued the most yellow and red cards, indicating a stricter officiating style.
- Defenders received the most fouls and cards compared to other positions.

### 🧬 Player Demographics
- Physical attributes like height and dominant foot revealed distinct player clusters, aiding in personalized training.

---

## 🏁 Conclusion
This project demonstrates how data analytics and machine learning can uncover valuable insights in football. By analyzing player performance, market trends, and attendance patterns, I've addressed key business questions and provided actionable recommendations. 

While the models provided moderate accuracy, the project highlights areas for further improvement, such as incorporating more diverse datasets and exploring advanced algorithms. The insights gained from this analysis can help football clubs, analysts, and fans make better decisions and appreciate the game through a data-driven lens.

As a data analyst, this project reflects my ability to transform raw data into actionable insights, use advanced analytics techniques, and communicate findings effectively through visualization and reporting.

---
