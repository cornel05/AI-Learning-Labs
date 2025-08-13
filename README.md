# AI-Learning-Labs
Labs (or Notebooks) of the AI/ML/DL Learning Journey
This repository contains Jupyter notebooks, datasets, and resources for machine learning exercises.

---

## 📂 Contents
- `notebooks/` – All lab notebooks
- `data/` – Associated datasets
- `images/` – Images used in notebooks

---

## 📄 View Labs & Run Online

| Lab | nbviewer Link | Open in Colab | Launch on Binder |
|-----|---------------|---------------|------------------|
| Regression_with_Single_Perceptron | [View in nbviewer](https://nbviewer.org/github/cornel05/AI-Learning-Labs/blob/main/notebooks/regression_with_single_perceptron.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cornel05/AI-Learning-Labs/blob/main/notebooks/regression_with_single_perceptron.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cornel05/AI-Learning-Labs/main?urlpath=lab/tree/notebooks/regression_with_single_perceptron.ipynb) |

> **Tip:** nbviewer renders the notebook with all saved outputs for easy reading without downloading.  
> **Colab** lets you edit and run the code interactively in the cloud.  
> **Binder** launches a JupyterLab environment in your browser.


---

## ▶️ Run Labs Online

**Google Colab**  
Click below to open in Colab with datasets auto-cloned:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<YOUR_USERNAME>/<YOUR_REPO>/blob/main/notebooks/C2_W3_Lab_1_Regression_with_Perceptron.ipynb)

**Binder (JupyterLab in browser)**  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/<YOUR_USERNAME>/<YOUR_REPO>/main?urlpath=lab/tree/notebooks/C2_W3_Lab_1_Regression_with_Perceptron.ipynb)

---

## 📦 Setup Locally

```bash
git clone https://github.com/cornel05/AI-Learning-Labs.git
cd AI-Learning-Labs
pip install -r requirements.txt
jupyter notebook
```

---

## **💡 Usage Tips**
1. **For nbviewer to display latest changes:**  
   - Push your changes to GitHub.
   - If old version shows, add `?flush_cache=true` to the URL once.

2. **Keep outputs in notebooks** if you want them visible in nbviewer.

3. **Use relative paths** to access CSVs/images so Colab, Binder, and local runs all work:
   ```python
   import pandas as pd
   df = pd.read_csv("../data/housing.csv")
    ```