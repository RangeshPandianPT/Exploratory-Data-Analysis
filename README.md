# Exploratory Data Analysis (EDA)

---

# 🎬 Trending Movies Data Analysis

This repository contains an exploratory data analysis (EDA) of a movie dataset featuring trending titles. The project includes visualizations, summary statistics, and data relationships, presented via both Python scripts and a Jupyter notebook.

---

## 📁 Contents

- Trending_Movies.csv — The dataset (10,000 records) containing movie metadata.
- analysis.py — Python script for summary statistics and visualizations.
- analysis.ipynb — Jupyter notebook with interactive plots and analysis.
- PNG Visualizations:
  - popularity_hist_box.png
  - vote_average_hist_box.png
  - vote_count_hist_box.png
  - correlation_matrix.png
  - pairplot.png

---

## 📊 Analysis Overview

### ✔ Summary Statistics
- Mean, median, and standard deviation for:
  - popularity
  - vote_average
  - vote_count

### ✔ Visualizations
- Histograms & boxplots for key numeric features
- Correlation heatmap
- Pairplot to identify clustering or trends

---



## 🔍 Key Observations

- Majority of movies have low popularity and vote counts.
- vote_average is typically between 5.5 and 7.0.
- Positive correlation exists between vote_count and popularity.

---

## 🛠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/trending-movies-analysis.git
   cd trending-movies-analysis

2. (Optional) Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3. Install dependencies:

pip install -r requirements.txt


4. Run the analysis:

Python script:

python analysis.py

Or open the Jupyter notebook:

jupyter notebook analysis.ipynb





---

🧩 Requirements

pandas

matplotlib

seaborn

jupyter (optional for notebook)


You can install them via:

pip install pandas matplotlib seaborn jupyter


---

📌 License

This project is open-source and available under the MIT License.


---

🤝 Contributing

Pull requests and improvements are welcome! Please feel free to fork this project and suggest changes.


---

📬 Contact

Created by [Your Name]
GitHub: yourusername

---

Let me know if you'd like the requirements.txt file or help publishing to GitHub!
