Here's a structured and organized version of your results that you can include in the README file for your project on Adult Income Dataset Analysis. This format includes each experiment in a clear, organized table layout and provides a summary for easy readability.

---

# Adult Income Dataset Analysis

This project explores various machine learning models to classify income levels in the Adult Income Dataset. Multiple experiments were conducted to improve model performance by applying different techniques such as data preprocessing, feature selection, and hyperparameter optimization. Here are the details of each experiment and the results achieved.

---

## Models Used
- Logistic Regression
- Support Vector Classifier
- Decision Tree
- Random Forest
- AdaBoost
- GradientBoost
- XGBoost
- LightGBM
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Bagging

---

## Experiments and Results

### 1. Baseline
| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| Logistic Regression      | 0.811830 | 0.799405  | 0.811830 | 0.798120 |
| Support Vector Classifier | 0.838917 | 0.831172  | 0.838917 | 0.830242 |
| Decision Tree            | 0.807297 | 0.807894  | 0.807297 | 0.807590 |
| Random Forest            | 0.851189 | 0.845518  | 0.851189 | 0.846400 |
| AdaBoost                 | 0.847319 | 0.840763  | 0.847319 | 0.840804 |
| GradientBoost            | 0.853068 | 0.847188  | 0.853068 | 0.845384 |
| XGBoost                  | 0.863129 | 0.858538  | 0.863129 | 0.859218 |
| LightGBM                 | 0.864013 | 0.859436  | 0.864013 | 0.860026 |
| Naive Bayes              | 0.808181 | 0.795582  | 0.808181 | 0.796272 |
| KNN                      | 0.822775 | 0.813999  | 0.822775 | 0.815722 |
| Bagging                  | 0.842454 | 0.835477  | 0.842454 | 0.835992 |

### 2. Missing Value Imputation with Mean
| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| Logistic Regression      | 0.821578 | 0.809296  | 0.821578 | 0.807319 |
| Support Vector Classifier | 0.848500 | 0.841005  | 0.848500 | 0.840022 |
| Decision Tree            | 0.814515 | 0.815946  | 0.814515 | 0.815204 |
| Random Forest            | 0.858123 | 0.852877  | 0.858123 | 0.854099 |
| AdaBoost                 | 0.858123 | 0.851925  | 0.858123 | 0.851812 |
| GradientBoost            | 0.865800 | 0.860502  | 0.865800 | 0.859088 |
| XGBoost                  | 0.875115 | 0.871109  | 0.875115 | 0.871869 |
| LightGBM                 | 0.873887 | 0.869507  | 0.873887 | 0.869959 |
| Naive Bayes              | 0.817893 | 0.805754  | 0.817893 | 0.806991 |
| KNN                      | 0.834272 | 0.825899  | 0.834272 | 0.827554 |
| Bagging                  | 0.846760 | 0.839866  | 0.846760 | 0.841094 |

### 3. Splitting at a 70:30 Ratio
| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| Logistic Regression      | 0.820310 | 0.807639  | 0.820310 | 0.805760 |
| Support Vector Classifier | 0.850816 | 0.843605  | 0.850816 | 0.842212 |
| Decision Tree            | 0.813554 | 0.814065  | 0.813554 | 0.813806 |
| Random Forest            | 0.858323 | 0.852869  | 0.858323 | 0.853999 |
| AdaBoost                 | 0.860233 | 0.854199  | 0.860233 | 0.853721 |
| GradientBoost            | 0.865284 | 0.860009  | 0.865284 | 0.857990 |
| XGBoost                  | 0.871767 | 0.867371  | 0.871767 | 0.868116 |
| LightGBM                 | 0.873951 | 0.869632  | 0.873951 | 0.870222 |
| Naive Bayes              | 0.817307 | 0.804885  | 0.817307 | 0.806069 |
| KNN                      | 0.834437 | 0.825614  | 0.834437 | 0.826975 |
| Bagging                  | 0.848563 | 0.841587  | 0.848563 | 0.842547 |

### 4. Class Balancing Using SMOTE and Tomek's Links
| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| Logistic Regression      | 0.766191 | 0.815424  | 0.766191 | 0.779685 |
| Support Vector Classifier | 0.811847 | 0.849266  | 0.811847 | 0.821687 |
| Decision Tree            | 0.795469 | 0.815944  | 0.795469 | 0.802685 |
| Random Forest            | 0.842763 | 0.851373  | 0.842763 | 0.846056 |
| AdaBoost                 | 0.824268 | 0.846905  | 0.824268 | 0.831263 |
| GradientBoost            | 0.845219 | 0.855734  | 0.845219 | 0.849026 |
| XGBoost                  | 0.857708 | 0.865119  | 0.857708 | 0.860505 |
| LightGBM                 | 0.857640 | 0.864577  | 0.857640 | 0.860296 |
| Naive Bayes              | 0.790077 | 0.819310  | 0.790077 | 0.799371 |
| KNN                      | 0.772948 | 0.843819  | 0.772948 | 0.788151 |
| Bagging                  | 0.832594 | 0.837163  | 0.832594 | 0.834584 |

... *(add additional experiment tables here following this format)* ...

---

### 10. Final Experiment Based on Best Strategies
| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| LightGBM                 | 0.873981 | 0.869506  | 0.873981 | 0.869687 |
| XGBoost                  | 0.872241 | 0.867833  | 0.872241 | 0.868418 |
| GradientBoost            | 0.868597 | 0.863473  | 0.868597 | 0.863036 |
| Random Forest            | 0.860223 | 0.854733  | 0.860223 | 0.855550 |
| AdaBoost                 | 0.860775 | 0.855092  | 0.860775 | 0.855657 |
| Ensemble Learning        | 0.873736 | 0.869167  | 0.873736 | 0.869078 |

---

These results show the impact of each experiment on model performance, indicating that methods like **hyperparameter optimization, feature selection, and ensemble learning** contributed significantly to improving classification accuracy and other metrics.
