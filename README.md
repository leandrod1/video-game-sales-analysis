# 🎮 Global Video Games Sales Analysis

[![MySQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)](game_project.sql)
[![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=flat-square&logo=tableau&logoColor=white)](TU_LINK_DE_TABLEAU_AQUI)

A data analysis project exploring historical global video game sales, regional preference dynamics, and console dominance using SQL and Tableau.

---

## 💡 Key Insights & Findings

* **Regional Market Shifts:** While Action and Shooter genres dominate North America and Europe, RPGs account for the largest market share in Japan.
* **Console Wars:** Platform X recorded the highest total sales volume, but Platform Y showed better historical consistency per title.
* **Peak Era:** The industry saw its highest sales volume between [YEAR] and [YEAR], heavily driven by [GENRE/PUBLISHER].

---

## 📊 Dataset & Data Preparation

The original dataset was sourced from [Kaggle Global Video Game Sales](https://www.kaggle.com/datasets/thedevastator/global-video-game-sales), containing **16,481 records**. However, to ensure data integrity and accuracy, I performed an extensive **data cleaning and enrichment process** using Excel before database ingestion:

* **Data Cleaning:** Handled missing values, standardized platform and game names, and corrected inaccurate data.
* **Data Enrichment:** Researched and manually updated missing release years and metadata to complete records.

**Key variables analyzed:**

* **Identification:** Game Name, Platform, Release Year, Genre, Publisher.
* **Regional Sales (in millions):** North America (NA), Europe (EU), Japan (JP), Other Regions.
* **Aggregates:** Global Sales and Global Ranking.

---

## 🔍 Project Structure & Analysis

The analysis covered 19 business queries categorized into 4 core areas:

1. **Top Performers:** Best-selling games globally vs. aggregated across platforms.
2. **Regional Breakdown:** Preferences across NA, EU, JP, and Rest of the World.
3. **Platform Performance:** Historical console leaderboards by region.
4. **Time Series:** Annual growth and sales trajectories.

---

## 👤 Author 

Leandro Soares: [LinkedIn Profile](https://www.linkedin.com/in/leandro-soares-91912097/)
