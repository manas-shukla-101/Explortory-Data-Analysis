# 🚦 Urban Mobility & Congestion: A Data-Driven Deep Dive

Urban commutes are more than just a daily hassle—they are a data problem. This project analyzes survey responses to move past "gut feelings" and prove exactly what is clogging our roads.

---

## 🛠️ The Toolkit
* **Data Wrangling:** Pandas for mode imputation and ordinal encoding.
* **Visualization:** Seaborn & Matplotlib for distribution analysis and proportional stacked bars.
* **Statistics:** Scipy for Chi-Square Contingency tests to validate urban hypotheses.

---

## 💡 Key Revelations
* **Infrastructure is the Enemy:** A definitive, non-random link exists between "Poor Road Infrastructure" and high-duration traffic delays ($p < 0.001$).
* **The Generational Shift:** Younger commuters (18-45) are statistically more likely to switch to public transit if reliability improves ($p = 0.041$).
* **Mode Matters:** Primary commute modes (Public vs. Private) show significantly different congestion frequency patterns ($p = 0.021$).

---

## 🚀 Analysis Workflow
1. **Cleaning:** Stripping whitespace, renaming columns, and handling missing values with mode imputation.
2. **Transformation:** Ordinal encoding of categorical features like `Age` and `CommuteTime`.
3. **EDA:** Visualizing distributions across residential areas and commute modes.
4. **Testing:** Statistical validation of causes vs. extra time added by congestion.

---

## 📈 Strategic Insights
* **Targeted Infrastructure:** Improving road quality directly alleviates long-duration congestion.
* **Policy Focus:** Launch transit reliability campaigns specifically targeting the 18–45 demographic to maximize adoption.
---
_Made with 💗 by Manas Shukla._
