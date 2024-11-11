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

### 5. Feature Selection (RFECV)
| Model                     | Accuracy | Precision | Recall  | F1 Score |
|---------------------------|----------|-----------|---------|----------|
| Logistic Regression       | 0.765918 | 0.814906  | 0.765918| 0.779392 |
| Support Vector Classifier | 0.810210 | 0.850432  | 0.810210| 0.820488 |
| Decision Tree             | 0.795469 | 0.815944  | 0.795469| 0.802685 |
| Random Forest             | 0.842763 | 0.851373  | 0.842763| 0.846056 |
| AdaBoost                  | 0.824268 | 0.846905  | 0.824268| 0.831263 |
| GradientBoost             | 0.845219 | 0.855734  | 0.845219| 0.849026 |
| XGBoost                   | 0.857640 | 0.864996  | 0.857640| 0.860421 |
| LightGBM                  | 0.858527 | 0.865529  | 0.858527| 0.861195 |
| Naive Bayes               | 0.795673 | 0.822725  | 0.795673| 0.804361 |
| KNN                       | 0.791988 | 0.842357  | 0.791988| 0.804332 |
| Bagging                   | 0.819900 | 0.827755  | 0.819900| 0.823138 |

### 6. Outliers Detection and Removal
| Model                     | Accuracy | Precision | Recall  | F1 Score |
|---------------------------|----------|-----------|---------|----------|
| Logistic Regression       | 0.747355 | 0.814517  | 0.747355| 0.763830 |
| Support Vector Classifier | 0.747355 | 0.742015  | 0.747355| 0.744510 |
| Decision Tree             | 0.736709 | 0.739957  | 0.736709| 0.738278 |
| Random Forest             | 0.804067 | 0.798308  | 0.804067| 0.800728 |
| AdaBoost                  | 0.814278 | 0.805641  | 0.814278| 0.809576 |
| GradientBoost             | 0.815192 | 0.812191  | 0.815192| 0.813304 |
| XGBoost                   | 0.816073 | 0.815036  | 0.816073| 0.815412 |
| LightGBM                  | 0.815824 | 0.811012  | 0.815824| 0.812966 |
| Naive Bayes               | 0.748117 | 0.747682  | 0.748117| 0.747707 |
| KNN                       | 0.751618 | 0.746730  | 0.751618| 0.749018 |
| Bagging                   | 0.786267 | 0.780326  | 0.786267| 0.783034 |

### 7. Stratified K-Fold Cross Validation
| Model                     | Accuracy | Precision | Recall  | F1 Score |
|---------------------------|----------|-----------|---------|----------|
| Logistic Regression       | 0.811822 | 0.797523  | 0.811822| 0.794325 |
| Support Vector Classifier | 0.832869 | 0.822994  | 0.832869| 0.818763 |
| Decision Tree             | 0.801626 | 0.803318  | 0.801626| 0.802365 |
| Random Forest             | 0.842635 | 0.836275  | 0.842635| 0.838021 |
| AdaBoost                  | 0.846751 | 0.839177  | 0.846751| 0.839635 |
| GradientBoost             | 0.855391 | 0.848832  | 0.855391| 0.848786 |
| XGBoost                   | 0.859035 | 0.854142  | 0.859035| 0.855308 |
| LightGBM                  | 0.859609 | 0.854462  | 0.859609| 0.855486 |
| Naive Bayes               | 0.809160 | 0.796251  | 0.809160| 0.794261 |
| KNN                       | 0.824434 | 0.812969  | 0.824434| 0.812489 |
| Bagging                   | 0.824802 | 0.816545  | 0.824802| 0.818914 |

### 8. Hyperparameter Optimization
| Model                     | Accuracy | Precision | Recall  | F1 Score |
|---------------------------|----------|-----------|---------|----------|
| Logistic Regression       | 0.804136 | 0.790233  | 0.804136| 0.793014 |
| Support Vector Classifier | 0.783184 | 0.757192  | 0.783184| 0.751825 |
| Decision Tree             | 0.818126 | 0.805679  | 0.818126| 0.806548 |
| Random Forest             | 0.830137 | 0.819609  | 0.830137| 0.818928 |
| AdaBoost                  | 0.798062 | 0.783529  | 0.798062| 0.786908 |
| GradientBoost             | 0.803931 | 0.789969  | 0.803931| 0.792754 |
| XGBoost                   | 0.802634 | 0.787906  | 0.802634| 0.790509 |
| LightGBM                  | 0.811984 | 0.798160  | 0.811984| 0.799163 |
| Naive Bayes               | 0.757388 | 0.807760  | 0.757388| 0.771457 |
| KNN                       | 0.820515 | 0.815718  | 0.820515| 0.817707 |
| Bagging                   | 0.819081 | 0.806236  | 0.819081| 0.805371 |

### 9. Ensemble Learning - Soft Voting
| Model             | Accuracy | Precision | Recall  | F1 Score |
|-------------------|----------|-----------|---------|----------|
| Ensemble Learning | 0.782229 | 0.784140  | 0.782229| 0.783153 |

### 10. Final Experiment Based on Best Strategies
| Model                     | Accuracy | Precision | Recall  | F1 Score |
|---------------------------|----------|-----------|---------|----------|
| LightGBM                  | 0.873981 | 0.869506  | 0.873981| 0.869687 |
| XGBoost                   | 0.872241 | 0.867833  | 0.872241| 0.868418 |
| GradientBoost             | 0.868597 | 0.863473  | 0.868597| 0.863036 |
| Random Forest             | 0.860223 | 0.854733  | 0.860223| 0.855550 |
| AdaBoost                  | 0.860775 | 0.855092  | 0.860775| 0.855657 |
| Ensemble Learning         | 0.873736 | 0.869167  | 0.873736| 0.869078 | 

---

These results demonstrate the impact of each experimental approach on model performance, highlighting how techniques such as hyperparameter optimization, feature selection, and ensemble learning effectively enhanced classification accuracy and other key metrics.
