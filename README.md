# Global Streaming Catalog Optimization & Strategic Growth Analysis

📈 **Project Evaluation Score:** 77/80 (Independent Industry Review)

## 📌 Project Overview
This project delivers an end-to-end Exploratory Data Analysis (EDA) on a global streaming catalog consisting of **8,807 media titles and 12 attributes**. The objective is to analyze the platform's content mix, regional alignment, audience demographics, and temporal trajectory to formulate data-driven global expansion and subscriber retention strategies.

## 🛠️ Tech Stack & Skills Demonstrated
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Data Engineering:** Memory optimization (categorical conversion), handling nested/multi-valued attributes (unnesting `director`, `cast`, `country`), distribution-based missing value imputation.
- **Statistical Analysis:** Non-graphical analysis, univariate/bivariate distributions, boxplot outlier detection, time-series growth analysis.

## 📊 Key Insights Uncovered
1. **Format Imbalance:** Discovered a major 70% Movie vs. 30% TV Show split across the global catalog.
2. **Regional Preferences:** Content appetites are heavily localized. The US and India show a strong preference for Movies, whereas South Korea strongly favors TV Shows.
3. **Temporal Growth:** Identified a massive content explosion starting from 2015 onwards, dominated by TV-MA (mature audience) demographic targeting.
4. **Viewer Churn & Seasonality:** Isolated critical viewing spikes in December/January and July, while identifying significant single-season TV show drop-offs (churn).

## 💡 Strategic Recommendations
- **Bi-Modal Content Budget:** Implement a 60/40 budget split favoring Movies in North America/India, and reverse it (favoring TV Shows) for East Asian expansion.
- **Holiday Content Drops:** Align major high-budget releases specifically with December/January and July windows to capture peak holiday viewership.
- **Retention Checkpoints:** To combat single-season churn, engineer 4-week analytical checkpoint gates to measure early audience drop-off and optimize renewal pacing.

## 📈 Evaluation Feedback & Iteration Notes
The project was evaluated by industry experts, securing full marks across problem definition, data cleaning, and business logic. 
* **Future Iteration:** The evaluation suggested adding a numerical correlation heatmap to further strengthen the bivariate visual analysis, which will be integrated into version 2.0 of this notebook.
