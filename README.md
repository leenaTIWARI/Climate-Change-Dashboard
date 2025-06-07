# 🌍 Climate Change Impact Dashboard

## 📌 Project Description
This dashboard visualizes and analyzes long-term climate trends using real-world datasets. It uncovers patterns and insights explaining the effects of climate change.

## 📁 Project Structure
- `data/`: Raw climate datasets
- `notebooks/eda.ipynb`: Data preprocessing & EDA notebook
- `visuals/`: Saved plots
- `requirements.txt`: Python dependencies

## ⚙️ How to Run
1. Clone the repo
2. Install dependencies
3. Run the notebook

## 📊 Key Features
- Cleaning and handling missing data
- Outlier detection
- Summary statistics
- Correlation analysis
- Visualization of global temperature trends

## 📈 Sample Visualizations
- Line chart: Temperature anomaly over years
- Box plot: Decadal comparison
- Correlation heatmap
- Interactive time series using Plotly

## 📚 Data Source
[Example: NASA GISTEMP](https://data.giss.nasa.gov/gistemp/)

# 🌍 Climate Change Impact Dashboard

A data-driven dashboard to explore, visualize, and interpret the long-term trends and impact of climate change using real-world datasets.

---

## 📌 Project Objectives

- Analyze global temperature anomalies over time
- Identify long-term warming trends and variability
- Correlate climate indicators such as CO₂, sea level rise, and ice extent
- Present insights through static and interactive visualizations
- Encourage data-driven awareness of climate change

---

## 📊 Features & Visualizations

| Type         | Description                                      | File                                     |
|--------------|--------------------------------------------------|------------------------------------------|
| 📈 Line Chart  | Global temperature anomaly (1880–present)         | `visuals/line_temp_trend.html`           |
| 📦 Box Plot   | Decadal temperature variability                  | `visuals/boxplot_decade.png`             |
| 🔥 Heatmap    | Correlation between climate indicators           | `visuals/correlation_heatmap.png`        |
| ✨ Interactive | Explore anomalies by year and decade            | `visuals/interactive_temp.html`          |

---

## 🎯 Interpretation Highlights

The visualizations tell a cohesive story:

- **Global temperatures are steadily rising**, especially after the 1980s.
- **Decadal shifts** show fewer cold outliers and consistently higher anomalies.
- Strong **positive correlations** exist between CO₂, sea level rise, and temperature.
- **Interactive filters** allow users to investigate how specific years fit into broader climate trends.

👉 Full storytelling analysis in [`interpretation_storytelling.md`](interpretation_storytelling.md)

---

## 📁 File Structure
climate-dashboard/
│
├── visuals/
│ ├── line_temp_trend.html
│ ├── interactive_temp.html
│ ├── boxplot_decade.png
│ └── correlation_heatmap.png
│
├── visual_dashboard.html
├── visual_style.css
├── visual_script.js
├── interpretation_storytelling.md
└── README.md


---

## 🛠️ How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/climate-dashboard.git
2. Open visual_dashboard.html
3. Make sure the visuals folder contains the necessary charts and HTML files.

🧠 Technologies Used
HTML, CSS, JavaScript

Python (for data analysis & visualization)

Plotly, Seaborn, Matplotlib (for generating charts)
