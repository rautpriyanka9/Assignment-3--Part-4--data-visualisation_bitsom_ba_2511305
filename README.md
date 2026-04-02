# Student Performance Analysis & Prediction

This project explores a dataset of 15 students to analyze academic performance across five subjects (Math, Science, English, History, and PE). It includes data visualization using Matplotlib and Seaborn, and a Machine Learning model to predict whether a student passes or fails.

##  Project Structure
* `students.csv`: The raw dataset containing student scores, attendance, and study hours.
* `part4_visualization_ml.ipynb`: The main Jupyter Notebook containing the analysis and code.
* `plot1_bar.png` to `plot5_line.png`: Visualizations created using Matplotlib.
* `seaborn_bar.png` & `seaborn_scatter_reg.png`: Visualizations created using Seaborn.
* `ml_feature_importance.png`: A chart showing which factors most influence student success.

##  Key Insights from Exploration
* **Top Student:** Identified the student with the highest overall average across all subjects.
* **Attendance Impact:** Analyzed the correlation between attendance percentage and passing grades.
* **Subject Averages:** Compared mean scores for passing vs. failing students to identify "bottleneck" subjects.

##  Machine Learning Model
I implemented a **Logistic Regression** model using `scikit-learn`. 
1. **Preprocessing:** Data was split into 80% training and 20% testing sets. Features were scaled using `StandardScaler` to ensure fair weight distribution.
2. **Performance:** The model predicts "Pass" (1) or "Fail" (0) based on academic and behavioral features.
3. **Feature Importance:** The model revealed which features (like study hours or math scores) were the strongest predictors of passing.

##  How to Run
1. Clone this repository.
2. Ensure you have Python installed along with the following libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn