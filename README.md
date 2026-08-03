# Malaria Forecasting and Analysis Project

## Project Structure

### 📂 data/
Contains all datasets used throughout the project, including:

- Raw malaria datasets
- Environmental datasets
- Socio-economic datasets
- Intermediate processed files
- Final cleaned datasets used for modeling

---

### 📂 data_analysis/
Contains all Python scripts used for:

- Data extraction and preprocessing
- Data cleaning and transformation
- Feature engineering
- Environmental data extraction from Google Earth Engine
- Model training and evaluation
- Forecast reconciliation and ensemble modeling
- Visualization and report generation

---

### 📂 images/
Contains all charts and visualizations generated during the analysis, including:

- Predicted vs Actual plots
- Feature Importance charts
- Cross-validation performance charts
- Model comparison visualizations
- Forecast reconciliation plots

Examples:

- `chart_district_predicted_vs_actual.png`
- `chart_district_feature_importance.png`
- `chart_state_cv_by_year.png`
- `chart_state_feature_importance.png`
- `chart_combined_comparison.png`
- `chart_combined_predicted_vs_actual.png`

---

### 📂 reports/
Contains report-ready outputs and summary files generated from the analysis, including:

- Model evaluation summaries
- Performance comparison reports
- Forecasting results
- Feature importance reports
- Final analytical outputs

Examples:

- `report_all_models_summary.csv`
- `district_model_metrics.csv`
- `state_model_cv_results.csv`
- `combined_model_comparison.csv`

---

## Workflow

1. Collect and preprocess malaria, environmental, and socio-economic datasets.
2. Extract environmental variables using Google Earth Engine.
3. Clean and transform all datasets into analysis-ready formats.
4. Engineer temporal, environmental, and socio-economic features.
5. Train district-level and state-level forecasting models.
6. Combine forecasts using hierarchical reconciliation techniques.
7. Generate performance metrics, visualizations, and final reports.
8. Store charts in the `images/` folder and reports in the `reports/` folder.

---

## Output

The project produces:

- Cleaned datasets for analysis
- District-level malaria forecasts
- State-level malaria forecasts
- Combined hierarchical forecasts
- Feature importance analyses
- Report-ready visualizations
- Summary performance reports
