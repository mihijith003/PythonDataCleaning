# 📱 Google Play Store Market Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VUnNHN7BA9BvIRwvdtvSwt9t6vItsQuy?usp=sharing)


## 📌 Overview
As an Android Developer and Data Enthusiast, I analyzed 10,000+ apps from the Google Play Store to understand market trends. This project focuses on data cleaning, feature engineering (converting raw size data), and visualization to answer real business questions about app pricing and user preference.

## 🛠️ Technologies Used
* **Python**: Core programming language.
* **Pandas**: For cleaning 10k+ rows of messy data (handling missing values, unit conversion).
* **Seaborn & Matplotlib**: For visualizing distributions and correlations.
* **Google Colab**: Development environment.

## 📊 Key Findings
1.  **Market Saturation**: The "Family" and "Game" categories are the most crowded, requiring high niche optimization for new entrants.
2.  **Pricing Strategy**: There is no strong negative correlation between Price and Rating, suggesting users are willing to pay for quality.
3.  **Size Matters**: The vast majority of apps with 1M+ installs are optimized to be under 50MB, identifying a critical threshold for mass adoption.

## 🧹 Data Cleaning Highlights
* **Unit Conversion**: Wrote custom logic to standardize 'Size' into a single 'MB' unit (converting 'k' and 'M').
* **String Manipulation**: Cleaned currency symbols (`$`) and install counts (`+`, `,`) to enable numerical analysis.
* **Glitch Handling**: Identified and removed corrupted rows (row 10472) that shifted data columns.

## 📈 Visuals
*(Note: Upload your charts to the repo and link them here, or just describe them)*
* **Bar Chart**: Top 10 Categories.
* **Box Plot**: Rating Spread (Free vs. Paid).
* **Scatter Plot**: Size vs. Installs (Clustered by Category).

---
*Created by [Mihijith003] - 2026*
