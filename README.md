# Project 1 – Large-scale Data Cleaning, Encoding, Exploration, and Predictive Modeling

## Overview

This project analyzes the NYC Yellow Taxi dataset to explore tipping behavior and build regression models to predict `tip_amount`.

The workflow includes:
- Data cleaning and preprocessing
- Feature engineering
- Exploratory data analysis
- Linear Regression and Lasso modeling
- Hyperparameter tuning
- Deployment-style testing

---

## Dataset

NYC Yellow Taxi trip records were used to analyze tipping behavior across time, location, and fare-related features.

---

## Repository Structure

- `training.ipynb`  
  Performs full preprocessing, model training, hyperparameter tuning (GridSearchCV), evaluation, and saves the tuned model.

- `test.ipynb`  
  Loads the saved model and performs inference only (no retraining).

- `best_lasso_model.pkl`  
  Tuned Lasso regression model used for prediction.

---

## Environment (Important)

This project was developed and tested using:

- **UFRC HiPerGator**
- **Python 3.10 kernel**
- pandas
- numpy
- scikit-learn
- joblib

The teaching team will evaluate the project using the HyperGator UFRC Python 3.10 environment.

No additional environment configuration is required when running on HyperGator.

---

## How to Run

### 1️ Training

Open and run all cells in:

training.ipynb

This notebook:
- Builds preprocessing pipelines
- Trains Linear Regression and Lasso models
- Performs hyperparameter tuning
- Saves the tuned model using:

```python
import joblib
joblib.dump(best_lasso, "best_lasso_model.pkl")
```

---

### 2️ Testing (Deployment Style)

Open and run:

test.ipynb

This notebook:
- Loads the saved model
- Recreates minimal feature engineering
- Generates predictions using `.predict()`
- Does NOT retrain the model

---

## Model Summary

- Final Model: Lasso Regression  
- Best alpha: 0.01  
- Test R² ≈ 0.52  
- 95% Confidence Interval ≈ [0.444, 0.580]  

The model explains approximately 52% of the variance in tipping behavior.

---

## Author

Daniel Hwang  
University of Florida


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

You can acknowledge any individual, group, institution or service.
* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)

## Thank you

<!-- If this is useful: [![Buy me a coffee](https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-1.svg)](https://www.buymeacoffee.com/catiaspsilva) -->
