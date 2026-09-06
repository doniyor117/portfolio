# Portfolio

Data analysis projects. Each one links to its own repo with the full notebook and write-up.

## Table of Contents

- [SQL](#sql)
- [Python](#python)
- [Power BI](#power-bi)
- [Learning](#learning)
- [About](#about)

---

## SQL

| Project | Question | Key finding | Tools |
| --- | --- | --- | --- |
| [Olist Seller Quality](https://github.com/doniyor117/olist-marketplace-analysis/tree/main/02-seller-quality) | What should Olist do with underperforming sellers: coach, warn, or drop? | Sellers who miss shipping deadlines a third of the time average a 3.86 review score against 4.30 for on-time sellers. But the worst-scoring "remove" tier is only 5.6% of sellers and 5.7% of 1-star reviews, so cutting them would barely move the marketplace's rating. Coaching the much larger "watch" tier (33% of orders, 41% of 1-star reviews) is where the real gain is. | SQL, DuckDB, JupySQL, pandas, matplotlib |

---

## Python

| Project | Question | Key finding | Tools |
| --- | --- | --- | --- |
| [Olist Delivery Promise Optimization](https://github.com/doniyor117/olist-marketplace-analysis/tree/main/01-delivery-estimates) | Should Olist shorten the delivery date it shows at checkout? | Promises run 12 days ahead of actual delivery, yet 7.6% still arrive late. A quantile model cuts ~3 days off the promise while lowering the late rate to 3.44%, against Olist's own 4.5%. | Python, pandas, LightGBM, Optuna |

---

## Power BI

| Project | Question | Key finding | Tools |
| --- | --- | --- | --- |
| [DataCo Supply Chain Profitability](https://github.com/doniyor117/dataco-supply-chain-analysis) | Which markets, categories, and shipping modes actually drive profit, not just revenue? | Faster shipping modes have worse late-delivery rates, not better ones: First Class averages 2.00 days but is late 95% of the time, against Standard Class at 4.00 days and 38% late. The promised window, not the shipping speed, is what's driving lateness. | Power BI, Power Query, DAX |

---

## Learning

The projects i worked on for learning.

| Repo | What's in it |
| --- | --- |
| [machine_learning_school21](https://github.com/doniyor117/machine_learning_school21) | ML algorithms written from scratch (decision trees, random forests, gradient boosting), plus clustering and dimensionality reduction exercises |

---

## About

Data analyst from Samarkand, Uzbekistan. Studying Management at Silk Road International University, and Data Science at School 21.

- [LinkedIn](https://www.linkedin.com/in/doniyor-khudoykulov/)
- <doniyor@khudoykulov.uz>
