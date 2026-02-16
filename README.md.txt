# 📊 YouTube Growth Analytics

 Objective
Analyze how engagement metrics (likes, comments) influence YouTube video views using exploratory data analysis and regression modeling.

---
 Dataset
- 600 YouTube videos
- Features: view_count, like_count, comment_count, category_id

---
 Exploratory Data Analysis
- View count distribution is highly right-skewed (skewness ≈ 8.0)
- Log transformation reduces skewness to near normal
- Likes show strong correlation with views (~0.70)
- Engagement rate has weak correlation with reach

---
 Modeling
| Model | R² Score |
|-------|----------|
| Raw Linear Regression | ~0.55 |
| Log-Transformed Model | ~0.84 |

Log transformation significantly improved predictive performance.

---

 Key Insights
- Viral videos create heavy skew in view distribution.
- Likes are strong predictors of views.
- Engagement intensity does not scale proportionally with reach.
- Growth pattern appears multiplicative rather than linear.

---

 Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
