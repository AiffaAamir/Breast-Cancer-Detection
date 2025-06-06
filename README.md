
# Breast Cancer Detection Using Machine Learning

---

## What is Breast Cancer?

Cancer arises when mutations occur in genes that control cell growth, causing cells to multiply uncontrollably. These abnormal cells form tumors, which can become malignant (cancerous).

Breast cancer specifically starts as a malignant tumor in breast tissue. As it progresses, cancer cells can spread (metastasize) through the lymphatic system—a network vital for immune defense—forming new tumors in distant parts of the body.

Although breast cancer is predominantly associated with women, men can also develop it, albeit less frequently. This project focuses primarily on breast cancer in women but much of the information is relevant to both genders.

---

## Facts and Figures

Breast cancer is the most common cancer among women and the second most common cancer worldwide. In 2018, over 2 million new cases were reported globally.

### Global Prevalence

| Region        | % of World Population | % of New Breast Cancer Cases | % of Breast Cancer Deaths |
| ------------- | --------------------- | ---------------------------- | ------------------------- |
| Asia          | 59                    | 39                           | 44                        |
| Africa        | 15                    | 8                            | 12                        |
| U.S. & Canada | 5                     | 15                           | 9                         |

*Data Source: Global Cancer Facts & Figures (3rd Edition)*

### Incidence Rates (per 100,000 women)

* **Highest:**

  * The Netherlands: 95.3
  * France: 94.6
  * U.S. (White population): 90.6

* **Lowest:**

  * Thailand: 25.6
  * Algeria: 29.8
  * India: 30.9

*Data Source: Global Cancer Facts & Figures (3rd Edition)*

### U.S. Estimates for 2019 (American Cancer Society)

* \~268,600 new invasive breast cancer cases in women
* \~62,930 new carcinoma in situ (non-invasive early form) cases
* \~41,760 deaths due to breast cancer

---

## Role of Machine Learning in Breast Cancer Detection

Mammography is the primary screening tool that uses X-ray images to detect breast cancer, even before symptoms appear. While effective in reducing mortality, mammograms have limitations:

* False positives can lead to unnecessary anxiety and tests
* False negatives may miss cancer
* Exposure to low-dose radiation

Interpreting mammogram images to distinguish malignant tumors from benign ones can be challenging. Here, machine learning (ML) models can assist by analyzing imaging data to improve diagnostic accuracy, potentially reducing errors and aiding physicians.

---

## Project Description

This project is inspired by research from:

* Doç. Dr. Ahmet MERT — Mechatronics Engineering, Faculty of Engineering and Natural Sciences
* Dr. Erdem Bilgili — Piri Reis University
* Dr. Aydin Akan — Izmir Katip Çelebi University, Turkey

It focuses on detecting breast cancer using machine learning techniques, particularly **Support Vector Machines (SVM)**, which have demonstrated high accuracy (\~97%) for this task.

### Dataset

We use the **Breast Cancer Wisconsin (Diagnostic) Dataset**, accessible via scikit-learn’s datasets API:

```python
from sklearn.datasets import load_breast_cancer
data = load_breast_cancer()
```

A CSV version of the dataset is also included in this repository for convenience.

---

## Results

* Initial SVM model accuracy: **96%**
* After normalization and hyperparameter tuning (C and Gamma): **97% accuracy**

---

## How to Access and Use This Project

1. **Fork** this repository
2. **Clone** it to your local machine:

   ```bash
   git clone <repo-url>
   ```
3. Explore, experiment, and build upon the existing code—make it your own!

---

## Final Thoughts

Working on this project has been an inspiring journey, blending engineering and medical science. Learning about the devastating impact of breast cancer motivates us to leverage technology for better detection and treatment.

If you decide to try this project, I hope you enjoy diving into the data, pushing your creativity, and imagining the possibilities machine learning can unlock.

Thank you for spending your valuable time here. I’d love to connect and collaborate—feel free to reach out via my GitHub profile!

If you found this project helpful or interesting, please consider leaving a ⭐️ on the repo — those stars really keep the motivation going!

Until next time, happy learning and stay curious! ❤️

---


