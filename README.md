
## 🚗 Automobile Data Analysis

This project explores an automobile dataset through exploratory data analysis (EDA), visualizations, and statistical testing to uncover relationships between features like engine size, horsepower, and price. The goal is to gain insights into what influences car pricing and vehicle characteristics.

---

### 📁 Dataset

* The dataset contains specifications of various cars including:

  * `price`
  * `engine-size`
  * `horsepower`
  * `curb-weight`
  * `fuel-type`
  * `body-style`, and more

---

### 📌 Objectives

* Clean and preprocess the data
* Perform statistical analysis and hypothesis testing
* Visualize relationships and distributions
* Build correlation heatmaps and scatter plots
* (Optional) Apply regression modeling or predictive analysis

---

### 🔧 Tools and Libraries

* Python (Pandas, NumPy, SciPy)
* Matplotlib & Seaborn for plotting
* Scikit-learn (if modeling is involved)
* Jupyter Notebook

---

### 📊 Key Visualizations

* Scatter plot: Engine Size vs Price
* Histogram of Car Prices
* Correlation Heatmap
* Pairplots of selected numerical features
* Boxplots by body-style or fuel-type

---

### 🧪 Statistical Tests Performed

* Shapiro-Wilk test for normality
* Pearson and Spearman correlation
* T-test (independent samples)
* ANOVA
* Chi-square (if applicable)

---

### 📁 Project Structure

```plaintext
├── data/
│   └── automobile.csv
├── notebooks/
│   └── analysis.ipynb
├── images/
│   └── plots and graphs
├── README.md
```

---

### ✅ Results Summary

* Strong correlation found between engine size and price (r ≈ 0.87, p < 0.01)
* Price distribution is right-skewed
* Significant variance in price across different body styles

---

### 📌 How to Run

1. Clone the repository
2. Open `analysis.ipynb` in Jupyter
3. Install required libraries using `pip install -r requirements.txt`
4. Run the notebook cells step by step

---

### 📚 License

This project is for educational and learning purposes.

---

