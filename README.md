## About

```yaml
name: Laura Diaz
located_in: Colombia

languages:
  spanish: Native
  english: Advanced
  french: Intermediate

education:
  - Postgraduate Specialization in GIS (ongoing)
  - B.Sc. in Geological Engineering

interests:
  - Machine Learning & Data Science
  - Spatial Data Analysis
  - Applied Mathematics

currently_learning:
  - Data Engineering
  - Advanced Machine Learning

goals:
  - Build machine learning engineering skills
```

## Projects

<details>
<summary><b>Satellite Image Segmentation (Machine Learning)</b></summary>
Unsupervised learning for land cover identification in multispectral satellite imagery.

- **Data:** Processed multispectral satellite imagery using `rasterio` and `NumPy`.
- **Modeling:** Applied **K-Means Clustering** ($K=5$) based on pixel-level band values.
- **Metrics:** Optimal cluster selection determined by **Calinski-Harabasz**, **Davies-Bouldin**, and **Inertia** metrics.
- **Validation:** Verified land cover categories through visual inspection.

[View in Google Colab](https://colab.research.google.com/drive/1ZBxasodY_2usQyABxV9DOhPAJ6Cpsmfp) | Documentation available in Spanish
</details>

<details>
<summary><b>House Price Prediction (MLOps)</b></summary>
Collaborative project to build a house price prediction pipeline and API.

- **Development:** Built the [**preprocessing pipeline**](https://github.com/Nikolas-1/MLDS6/blob/master/scripts/preprocessing/main.py) and developed the [**predictive models**](https://github.com/Nikolas-1/MLDS6/blob/master/scripts/training/model_training.ipynb).
- **Performance:** Optimized model selection (Linear Regression → **XGBoost**), improving **MAE** from ~110K to ~65K.
- **Version Control:** Used **DVC** for data versioning and **MLflow** for experiment tracking.
- **Collaboration:** Partnered with [Nikolas](https://github.com/Nikolas-1), who handled the initial data exploration, FastAPI integration, and Railway deployment.

[Project Repository](https://github.com/Nikolas-1/MLDS6) | Documentation available in Spanish
</details>
