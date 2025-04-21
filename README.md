# Equite

This project focuses on detecting and mitigating bias in loan approval prediction systems using fairness-aware machine learning methods. It incorporates pre-processing, in-processing, and post-processing techniques to ensure ethical and equitable outcomes across sensitive attributes like gender and race.

## 🧠 Motivation

Machine learning models trained on real-world data often carry societal biases. In the finance sector, such bias can lead to unfair loan decisions. This project aims to build fair and accurate models that respect core fairness metrics while retaining predictive power.


## 📊 Dataset

Used a publicly available loan dataset containing sensitive attributes such as gender and race. Data preprocessing steps included:
- Handling missing values
- Encoding categorical variables
- Splitting into training and testing sets

## 🛠️ Methodology

### 🔄 Pre-processing
- **Disparate Impact Remover (DIR)** from AIF360: Rebalances feature distribution across groups.

### 🧠 In-processing
- **Fairlearn’s fairness-constrained learners**: Enforces fairness metrics during model training.

### ✅ Post-processing
- **Calibrated Equalized Odds** from AIF360: Adjusts model outputs to achieve fairness in predicted outcomes.

## 🧪 Evaluation Metrics

A combination of performance and fairness metrics:
- Accuracy: 83.11%
- Precision, Recall, F1-score
- Disparate Impact
- Demographic Parity

## 📈 Results & Visualizations

Radar charts and scatter plots were used to visualize the fairness-performance trade-off. The fairness-aware model showed a significant reduction in bias while maintaining high accuracy.

## 🛠️ Tools & Libraries

- Python
- Scikit-learn
- AIF360
- Fairlearn
- Pandas, NumPy, Matplotlib

## 📚 References

- Barocas, Hardt, & Narayanan. *Fairness and Machine Learning*
- IBM Research. *AI Fairness 360 Toolkit*
- Fairlearn Documentation
- Hardt et al. *Equality of Opportunity in Supervised Learning*

---


