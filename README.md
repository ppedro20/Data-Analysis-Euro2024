# ⚽ Data Analysis of FIFA World Cup Final 2022 (Argentina vs France)

A data analytics project analyzing the **FIFA World Cup 2022 Final** between Argentina and France using **event-level match data** from [StatsBomb Open Data](https://github.com/statsbomb/open-data).
It features **pass networks**, **player heatmaps**, and key match statistics visualized in an interactive **Tableau dashboard**.

---

## 📊 Dashboard Preview

🔗 **[View Tableau Dashboard Here](https://public.tableau.com/app/profile/your-link)**

<img src="preview.png" alt="Dashboard Preview" width="800"/>

---

## 🚀 Project Overview

| Feature            | Description                                     |
| ------------------ | ----------------------------------------------- |
| 📈 Pass Networks   | Visualize team passing structure & connectivity |
| 🔥 Player Heatmaps | Show ball touches & movement patterns           |
| 📋 Match Stats     | Summarize xG, possession, shots, pass accuracy  |
| 🌐 Interactive     | Filters for teams, players, and match minutes   |

---

## 🗂️ Project Structure

```
fifa_wc_2022_final/
├── data/
│   ├── 3857256.json         # Raw StatsBomb event data
│   ├── passes.csv           # Cleaned passes data
│   ├── touches.csv          # Player ball touches
├── notebooks/
│   └── preprocess.ipynb     # Python script for data cleaning
├── tableau_dashboard.twb    # Tableau workbook file
├── README.md                # Project documentation
└── preview.png              # Dashboard screenshot
```

---

## 🔥 Tools & Technologies

- 🐍 **Python**: pandas, numpy, statsbombpy (data cleaning & preprocessing)
- 📊 **Tableau**: interactive dashboards (heatmaps, networks, KPIs)
- 📦 **StatsBomb Open Data**: raw JSON match data
- 📁 CSV for Tableau-ready datasets

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

### 4️⃣ Open in Tableau

- Load `tableau_dashboard.twb` in Tableau Desktop or Tableau Public.
- Explore heatmaps, pass networks, and match statistics.

---

## 📌 License

This project uses **StatsBomb Open Data** under the Creative Commons Attribution 4.0 International (CC BY 4.0).

---

## 👨‍💻 Author

Pedro Afonso Monteiro Pedro
📧 ppedroodev@gmail.com | [LinkedIn](https://www.linkedin.com/in/ppedrodev/) | [GitHub](https://github.com/ppedro20)
