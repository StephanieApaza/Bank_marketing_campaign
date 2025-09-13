# Bank Marketing Campaign Analysis

## Overview
This project analyzes the customer profiles and the impact of marketing campaigns on the acceptance of financial products. It combines client, campaign, and economic factors data to identify patterns and factors that influence campaign success.

## 🎯Business Questions
- Which customer profiles are more likely to accept a campaign?
- How do the number and duration of contacts affect the outcome?
- What impact do economic factors have on loan acceptance?
- What improvements can be implemented to increase the effectiveness of future campaigns?

## 💡Key findings
- **Credit default:** The vast majority of clients do not default on loans, representing a low-risk profile.
- **Customer profile:** Most successful responses come from customers aged 31-50, married, with a university degree, and working in occupations such as administration, technician, and services.
- **Campaign performance:** There was a 238.44% improvement compared to the previous year.
- **Contact strategy:** The best results are achieved with 1 to 3 contacts and calls lasting 1 to 10 minutes. Longer interactions do not significantly increase success.
- **Economic condition:** Effectiveness decreases as the Euribor and const_price_idx rise, showing customer sensitivity to macroeconomic conditions.

## 🧭Conclusion
The analysis shows that marketing strategies focused on customers aged 31-50, with higher education and stable jobs, maximize the success rate. Additionally, limiting campaign contacts to 1-3 short interactions enhances effectiveness. However, macroeconomic conditions such as euribor and const_price_idx have a direct influence on customer decisions, meaning campaigns must adapt to the economic context to sustain or improve results.

## 🛠️Built with
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook for exploratory analysis and visualization.
