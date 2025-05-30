# Tucson Crime Analysis

**Authors:** Apurbo Barua & Asifur Rahman  
**Semester:** Spring 2025

## Project Objective

To investigate the correlation between neighborhood income levels and arrest activity during late-night hours in Tucson, AZ.  
We hypothesized that low-income neighborhoods experience disproportionately more arrests during 12 AM–6 AM.

## Key Steps & Methods

- **Data Sources:**  
  - Tucson Police Arrests  
  - Neighborhood Income Data  
  - City of Tucson Open Data

- **Feature Engineering:**  
  - Derived time periods (Daytime, Evening, Late Night)  
  - Handled missing data, encoded categories

- **Machine Learning:**  
  - Used **Random Forest Classifier**  
  - Balanced dataset via oversampling  
  - Applied **GridSearchCV** for hyperparameter tuning

- **Evaluation Metrics:**  
  - Accuracy: ~44%  
  - Precision, Recall, F1-score used per class  
  - Confusion Matrix & Feature Importance plots

## Key Insights

- **Arrest Time Trends:** Daytime arrests dominate; late-night arrests show unique patterns.
- **Demographics:** Higher arrest rates in Hispanic or Latino individuals.
- **Crime Types:** Most common offenses include misdemeanors like Failure to Appear.
- **Age Group:** 26–36 age range had the highest number of arrests.

## Challenges

- Absence of a usable `TimePeriod` field (derived manually).
- Class imbalance corrected through oversampling.
- Initial models (Logistic Regression) underperformed; replaced with Random Forest.

## Future Work

- Integrate weather, location & community resource data. 
- Explore Gradient Boosting or Neural Networks. 
- Develop policy recommendations for data-driven policing. 

## 📫 Contact

- asifrahman@arizona.edu
