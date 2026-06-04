# Advanced Behavioral Modeling: SEM & Random Forest Regression

This repository hosts the advanced computational and structural modeling phase of the student neuroplasticity and cognition project. Utilizing primary survey data ($N = 212$), this analysis bridges behavioral science and machine learning by executing Structural Equation Modeling (SEM) alongside a Random Forest Regressor to map out the latent, mediated pathways driving student success.

## 🔗 Project Links
* **Interactive Notebook:** [Google Colab Implementation](https://colab.research.google.com/drive/1dyuehRhrNi03AlcdiEP_C7bl-Fluv1xv?usp=sharing)
* **Kaggle Dataset:** [Dataset Link](https://www.kaggle.com/datasets/muskanirfan29/neuroplasticity-cognition-and-academic-performance)

---

## 📐 1. Structural Equation Modeling (SEM) Results
The SEM framework evaluated how lifestyle choices and cognitive traits interact to influence academic results. 

### Core SEM Pathways
* **The Dominant Pathway:** A strong, highly significant positive relationship was found between `cognitive_engagement` and `academic_performance`. This establishes mental involvement, sustained attention, and active learning as the primary drivers of success.
* **The Mediated Pathway:** Neuroplasticity-enhancing behaviors (sleep, exercise, nutrition) showed a positive but weak direct influence on cognitive engagement. 
* **Mediation Effect:** Lifestyle behaviors do not have a direct significant impact on academic performance. Instead, their influence is entirely indirect, operating through cognitive engagement. Behavioral habits only boost marks when they successfully translate into higher cognitive involvement.

### Model Fit Indices (Excellent Fit)
The structural model demonstrated outstanding statistical robustness and validity:
* **RMSEA:** $0.00$ (indicating a mathematically perfect fit)
* **CFI:** Exceeded the conventional adequacy thresholds 
* **Chi-Square Test:** Yielded a non-significant $p$-value, confirming absolute consistency between our hypothesized model and the observed data.

---

## 🤖 2. Machine Learning Analysis (Supporting Evidence)
To cross-validate the SEM pathways, a **Random Forest Regression** model was trained to predict academic performance.

### Model Metrics & Insights
* **Model Fit ($R^2$):** $\approx 0.17$. The model explains 17% of the variance in academic performance, indicating that academic outcomes are driven by highly complex, latent variables beyond basic observed behaviors.
* **Feature Importance:** Rather than optimized prediction, this model served as feature validation. **Cognitive engagement emerged as the single most influential predictor**, contributing the highest share to the model's predictions, which strongly cross-validates and reinforces our SEM framework.
* **Secondary Features:** Exercise-related cognitive benefits and digital habits (e.g., doomscrolling) showed moderate feature importance, while sleep duration and screen time showed the lowest predictive influence.

---

## 👥 Project Team & Credits

* **Muskan Irfan (Main Author):** Lead Researcher who conceptualized, designed, and directed the entire study lifecycle. Built the Structural Equation Model (SEM) and machine learning pipeline alongside Taha to comprehensively map and understand the complex behavioral relationships within the data.
* **Muhammad Taha:** Data Scientist / Engineer who collaborated closely with Muskan to construct the Structural Equation Model (SEM) and implement the Random Forest regression pipeline.
* **Muhammad Yasir Qurashi:** Partner Data Analyst who executed the foundational data analysis workflow, providing the critical statistical processing that directly enabled the cross-validation and deep understanding of the model relationships.
