# 🌍 Climate Change Impact Dashboard

## 📌 Project Description
This dashboard visualizes and analyzes long-term climate trends using real-world datasets. It uncovers patterns and insights explaining the effects of climate change.

---

## 📁 Project Structure
- `data/`: Raw climate datasets  
- `notebooks/eda.ipynb`: Data preprocessing & exploratory data analysis notebook  
- `visuals/`: Saved plots and interactive charts  
- `requirements.txt`: Python dependencies  

---

## ⚙️ How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/climate-dashboard.git
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook to preprocess data and generate visualizations:
   jupyter notebook notebooks/eda.ipynb
4. Open the dashboard in your browser by opening:
   open visual_dashboard.html
## 📊 Key Features

- Data cleaning and handling of missing values  
- Outlier detection techniques  
- Summary statistics calculation  
- Correlation analysis of climate indicators  
- Visualization of global temperature trends and climate data  

---

## 📈 Visualizations Included

| Visualization Type | Description                                   | File Location                      |
|--------------------|-----------------------------------------------|----------------------------------|
| 📈 Line Chart       | Global temperature anomaly (1880–present)    | `visuals/line_temp_trend.html`   |
| 📦 Box Plot        | Decadal temperature variability                | `visuals/boxplot_decade.png`     |
| 🔥 Heatmap          | Correlation matrix between climate indicators | `visuals/correlation_heatmap.png`|
| ✨ Interactive Plot | Year-wise temperature anomalies with filtering| `visuals/interactive_temp.html`  |

---

## 🎯 Interpretation Highlights

The visualizations tell a cohesive story about climate change trends:

- **Global temperatures are steadily rising**, especially accelerating after the 1980s.  
- **Decadal shifts** show fewer cold outliers and a higher median temperature anomaly.  
- Strong **positive correlations** exist between CO₂ levels, sea level rise, and temperature increases.  
- **Interactive filters** enable detailed exploration of how specific years and decades contribute to climate trends.  

For a detailed storytelling analysis, see [`interpretation_storytelling.md`](interpretation_storytelling.md).

---

## 📁 Complete File Structure

climate-dashboard/
│
├── data/
│ └── (raw climate datasets)
│
├── notebooks/
│ └── eda.ipynb
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

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Data Analysis & Visualization:** Python, Plotly, Seaborn, Matplotlib  

---

## 📚 Data Source

This project uses simulated datasets inspired by [NASA GISTEMP](https://data.giss.nasa.gov/gistemp/) global temperature records.

---

## 📜 License

MIT License
If you want, I can help you generate any of these files or set up GitHub Pages for easy demo access!
---
