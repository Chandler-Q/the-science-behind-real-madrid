# ⚽ Real Madrid Passing Network Analysis — UEFA Champions League Finals (2016–2018)

This repository contains a Jupyter Notebook analyzing **Real Madrid’s passing networks** in the UEFA Champions League finals (2016–2018) using **StatsBomb Open Data**.

The project applies **network science** and **data visualization** to explore how passing structures contributed to Real Madrid’s three consecutive Champions League titles.

---

## 📂 Repository Contents
- `RealMadrid_PassingNetworks_Analysis.ipynb` → Main notebook with complete analysis  
- `requirements.txt` → Python dependencies  
- `images/` → Team logos used in visualizations  
- `data/` → StatsBomb JSON event & lineup data (already included)  
- `football_icon.png` → Icon used in shot map visualizations to mark goals  

---

## ✨ Key Features
- Load and process **StatsBomb JSON event & lineup data**  
- Construct **passing networks** using NetworkX  
- Compute tactical metrics:
  - Degree, betweenness, closeness, eigenvector centrality  
  - Pass density, total passes  
  - Expected Goals (xG) timelines  
- Visualizations:
  - Full-match passing networks  
  - Pre-goal (−5 min) sub-networks  
  - Shot maps with assists and xG values (⚽ icons displayed via `football_icon.png`)  
  - Passing start heatmaps  

---

## 🚀 Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
```

---

## ▶️ Usage
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook RealMadrid_PassingNetworks_Analysis.ipynb
   ```

2. Run all cells to reproduce the analysis.  

   - The required **StatsBomb event & lineup JSON files** are already provided in the `data/` folder.  
   - Team logos are included under `images/` and will be automatically displayed in the visualizations.  
   - The file `football_icon.png` is used to render goal icons in shot maps.  

---

## 📚 Data Source
- **StatsBomb Open Data**  
  Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).  
  Free for research and teaching purposes, not for commercial use.  

---

## 📜 License
- Notebook & code: MIT License  
- Data: StatsBomb Open Data, CC BY-NC-SA 4.0  
