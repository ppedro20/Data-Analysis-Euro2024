# ⚽ Data Analysis of EURO 2024

A data analytics project analyzing the **EURO 2024** using **event-level match data** from [StatsBomb Open Data](https://github.com/statsbomb/open-data).
It features **pass networks**, **player heatmaps**, and key match statistics visualized in an interactive **Streamlit dashboard**.

## 🚀 Project Overview

| Feature            | Description                                     |
| ------------------ | ----------------------------------------------- |
| 📈 Pass Networks   | Visualize team passing structure & connectivity |
| 🔥 Player Heatmaps | Show ball touches & movement patterns           |
| 📋 Match Stats     | Summarize xG, shots, goals                      |
| 🌐 Interactive     | Filters for teams and players                   |

---

## 🗂️ Project Structure

```
euro_2024/
├── data/
│   ├── imgs/         		# Folder for every virtualization created
│   ├── passes.csv           	# Cleaned passes data
│   └── touches.csv          	# Player ball touches
├── notebooks/
│   ├── passing-networks.ipynb	# Python script for the creation of passing networks
│   └── preprocess.ipynb     	# Python script for data cleaning
├── streamlit.py            	# Streamlit workbook file
├── README.md                	# Project documentation
└── preview.png              	# Dashboard screenshot
```

---

## 🔥 Tools & Technologies

- 🐍 **Python**: pandas, numpy, statsbombpy (data cleaning & preprocessing)
- 📊 **Streamlit**: interactive dashboards (heatmaps, networks, KPIs)
- 📦 **StatsBomb Open Data**: raw JSON match data
- 📁 CSV for datasets


## 📌 License

This project uses **StatsBomb Open Data** under the Creative Commons Attribution 4.0 International (CC BY 4.0).

---

## 👨‍💻 Author

Pedro Afonso Monteiro Pedro
📧 ppedroodev@gmail.com | [LinkedIn](https://www.linkedin.com/in/ppedrodev/) | [GitHub](https://github.com/ppedro20)
