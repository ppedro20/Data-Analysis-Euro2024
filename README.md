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
fifa_wc_2022_final/
├── data/
│   ├── imgs/         		# Folder for every virtualization created
│   ├── passes.csv           	# Cleaned passes data
│   └── touches.csv          	# Player ball touches
├── notebooks/
│   ├── passing-networks.ipynb	# Python script for the creation of passing networks
│   └── preprocess.ipynb     	# Python script for data cleaning
├── tableau_dashboard.twb    	# Tableau workbook file
├── README.md                	# Project documentation
└── preview.png              	# Dashboard screenshot
```

---

## 🔥 Tools & Technologies

- 🐍 **Python**: pandas, numpy, statsbombpy (data cleaning & preprocessing)
- 📊 **Streamlit**: interactive dashboards (heatmaps, networks, KPIs)
- 📦 **StatsBomb Open Data**: raw JSON match data
- 📁 CSV for datasets

---

## 📝 Data Source

- [StatsBomb Open Data GitHub](https://github.com/statsbomb/open-data)
- Match ID: `3857256` – FIFA World Cup 2022 Final (Argentina vs France)

---

## ⚡ Quick Start Guide

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/fifa_wc_2022_final.git
cd fifa_wc_2022_final
```

### 2️⃣ Install Dependencies

```bash
pip install pandas numpy statsbombpy
```

### 3️⃣ Preprocess Data

Run the preprocessing script to create `passes.csv` and `touches.csv`:

```bash
python notebooks/preprocess.py
```

## 📌 License

This project uses **StatsBomb Open Data** under the Creative Commons Attribution 4.0 International (CC BY 4.0).

---

## 👨‍💻 Author

Pedro Afonso Monteiro Pedro
📧 ppedroodev@gmail.com | [LinkedIn](https://www.linkedin.com/in/ppedrodev/) | [GitHub](https://github.com/ppedro20)
