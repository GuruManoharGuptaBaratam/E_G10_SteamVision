# 🎮 Steam Games Analytics: Predicting Game Success

A data analytics project focused on identifying the key factors that drive the commercial success of games on Steam and building a decision framework for developers and publishers.

---

## 📌 Problem Statement

The gaming industry is highly competitive, with thousands of games released each year. However, only a small percentage achieve meaningful player reach.

This project answers:

> **What factors drive the commercial success of a game, and how can we predict whether a game will succeed or fail?**

---

## 📊 Dataset

- Source: Steam game data (Kaggle + Steam APIs)
- Records: **66,427 games**
- Time Period: **2006 – 2023**
- Features: 20 columns including:
  - Rating
  - Total Reviews
  - All-Time Peak Players
  - Genre
  - Review Percentage

---

## ⚙️ Project Pipeline

The project follows an end-to-end data analytics workflow:

1. **Data Extraction**
   - Merged multiple Steam datasets

2. **Data Cleaning**
   - Removed duplicates (1,100+ records)
   - Handled missing values (~19,000 rows)
   - Standardized formats and categories

3. **Exploratory Data Analysis**
   - Identified trends and patterns in engagement and success

4. **Statistical Analysis**
   - Correlation analysis
   - Hypothesis testing
   - Regression modeling

5. **Dashboard Development**
   - Built interactive Tableau dashboard for decision-making

---

## 📐 KPI Framework

Game success is not one-dimensional. We define success using:

- 🎯 **Quality** → Rating  
- 📈 **Engagement** → Peak Players  
- 🌍 **Reach** → Total Reviews  

### ⭐ Success Score (CSI)
- success_score = (0.4 × normalized peak players + 0.6 × normalized total reviews) × 100


### 📊 Market Categories

- **Hit** → High reach & engagement  
- **Average** → Moderate performance  
- **Niche / Fail** → Low traction  

---

## 🔍 Key Insights

### 1. Most games fail to scale
- 61% have <50 reviews  
- 80% have <100 peak players  

### 2. Review volume drives success
- Correlation (reviews vs peak): **0.67**
- Correlation (rating vs peak): **0.04**

👉 Visibility matters more than rating

### 3. Genre impacts success
- Free-to-play leads in scale  
- RPG and Action outperform others  

### 4. Quality is not enough
- High ratings alone do not guarantee success  

---

## 📊 Statistical Findings

- 📈 Correlation: Strong relationship between reviews and peak players  
- 📉 Regression:  
  - R² = **0.74** → Reviews explain 74% of engagement variation  
- 📊 Hypothesis Testing:
  - RPG significantly outperforms Casual (p < 0.001)

---

## 📊 Tableau Dashboard

Interactive dashboard to explore:

- KPI overview (ratings, engagement, reach)
- Genre-based performance
- Relationship between reviews and success
- Success segmentation

🔗 **Tableau Public Link:** *(Add here)*  

---

## 💡 Recommendations

1. 🚀 Focus on early visibility and discovery  
2. 📢 Prioritize review generation and community engagement  
3. 🎮 Choose genres strategically  
4. 📊 Track early performance indicators  
5. ⚙️ Use Success Score for decision-making  

---

## 📈 Business Impact

- Better launch strategy planning  
- Reduced risk of failure  
- Faster identification of underperforming games  
- Data-driven development decisions  

> Nearly **60% of games fail**, making data-driven strategy critical.

---

## ⚠️ Limitations

- No direct revenue data  
- External factors (pricing, marketing) not included  
- Correlation does not imply causation  

---

## 🔮 Future Scope

- Machine learning model for success prediction  
- Sentiment analysis on reviews  
- Real-time performance dashboard  
- Integration with pricing and revenue data  

---

## 👥 Team

| Role | Member |
|------|--------|
| Project Lead | Member 1 |
| Data Lead | Member 2 |
| ETL Lead | Member 3 |
| Analysis Lead | Member 4 |
| Visualization Lead | Member 5 |
| Strategy & PPT | Member 6 |

---

## 🔗 Links

- 📂 GitHub Repository  
  https://github.com/GuruManoharGuptaBaratam/E_G10_SteamVision  

- 📊 Tableau Dashboard  
  *(Add link)*  

---

## 🧠 Key Takeaway

> **Game success is driven more by visibility and player engagement than by ratings alone.**

Even small improvements in early traction can significantly increase the chances of success.
