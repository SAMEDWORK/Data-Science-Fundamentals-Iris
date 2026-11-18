## Project Summary
This project analyzes the classic Iris dataset (150 flowers, 3 species, 4 measurements in cm) using Python, Pandas, NumPy, Matplotlib, and Seaborn. It covers dataset understanding, Python fundamentals, data cleaning, descriptive statistics, and exploratory data analysis (EDA), with the findings documented in a written report.
## Key Findings
- **Clean, balanced data:** no missing values, 50 samples per species. One duplicate row was found and removed.
- **Petal measurements are the best predictors:** petal length and petal width have the highest variance and are very strongly correlated (r ≈ 0.96).
- **Species separate clearly by petal size:** average petal length is about 1.5 cm for setosa, 4.3 cm for versicolor, and 5.6 cm for virginica.
- **Setosa is fully separable:** it forms a distinct cluster, while versicolor and virginica partially overlap, so combining features works better than a single threshold.
- **Sepal width is the weakest feature:** it has the lowest variance and weak negative correlations with the other features.
**Conclusion:** petal length and petal width should be the primary features for classifying iris species, with sepal measurements as supporting features.
