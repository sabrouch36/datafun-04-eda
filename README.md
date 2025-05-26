# datafun-04-eda 


In this project, we begin working with real-world data using Python and Jupyter Notebooks. We will practice data cleaning, exploration, and basic visualizations to uncover insights from datasets.

# Exploratory Data Analysis - Iris Dataset

This project demonstrates basic exploratory data analysis (EDA) using a Jupyter Notebook.

We used the built-in **Iris dataset** to explore relationships between features with visualizations such as:

-  Pairplot by species (Seaborn)
-  Correlation heatmap (numeric-only)
-  A custom bar chart showing **course progress** using `matplotlib`

This notebook serves as both a practice in using Jupyter, and as a demonstration of basic EDA skills.

---

---

##  Tools Used
- Python 3.13.2
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

---

## 💡 Extra Example
We included a small extra example to visualize **course progress**:  
A simple bar chart showing completed vs. remaining weeks in the course.

```python
# Example: Custom progress chart
total_weeks = 7
weeks_completed = 4
weeks_remaining = total_weeks - weeks_completed

