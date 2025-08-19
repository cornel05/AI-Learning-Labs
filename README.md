# AI-Learning-Labs
Labs (or Notebooks) of the AI/ML/DL Learning Journey
This repository contains Jupyter notebooks, datasets, and resources for AI/ML/DL exercises.

---

## 📂 Contents
- `notebooks/` – All lab notebooks
- `data/` – Associated datasets
- `images/` – Images used in notebooks

---

## 📄 View Labs & Run Online

### 🔹 Regression Labs
| Lab | nbviewer | Colab | Binder |
|-----|----------|-------|--------|
| Regression with Single Perceptron | [View in nbviewer](https://nbviewer.org/github/cornel05/AI-Learning-Labs/blob/main/notebooks/regression_with_single_perceptron.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cornel05/AI-Learning-Labs/blob/main/notebooks/regression_with_single_perceptron.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cornel05/AI-Learning-Labs/main?urlpath=lab/tree/notebooks/regression_with_single_perceptron.ipynb) |

---

### 🔹 Classification Labs
| Lab | nbviewer | Colab | Binder |
|-----|----------|-------|--------|
| Classification with Single Perceptron | [View in nbviewer](https://nbviewer.org/github/cornel05/AI-Learning-Labs/blob/main/notebooks/classification_with_single_perceptron.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cornel05/AI-Learning-Labs/blob/main/notebooks/classification_with_single_perceptron.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cornel05/AI-Learning-Labs/main?urlpath=lab/tree/notebooks/classification_with_single_perceptron.ipynb) |

---

### 🔹 Optimization Labs
| Lab | nbviewer | Colab | Binder |
|-----|----------|-------|--------|
| Optimization Using Newton Method | [View in nbviewer](https://nbviewer.org/github/cornel05/AI-Learning-Labs/blob/main/notebooks/optimization_using_newton_method.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cornel05/AI-Learning-Labs/blob/main/notebooks/optimization_using_newton_method.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cornel05/AI-Learning-Labs/main?urlpath=lab/tree/notebooks/optimization_using_newton_method.ipynb) |

---

### 🔹 Computer Vision Labs
| Lab | nbviewer | Colab | Binder |
|-----|----------|-------|--------|
| OpenCV - NumPy Image Processing | [View in nbviewer](https://nbviewer.org/github/cornel05/AI-Learning-Labs/blob/main/notebooks/opencv_numpy_image_processing.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cornel05/AI-Learning-Labs/blob/main/notebooks/opencv_numpy_image_processing.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cornel05/AI-Learning-Labs/main?urlpath=lab/tree/notebooks/opencv_numpy_image_processing.ipynb) |
> **Tip:** nbviewer renders the notebook with all saved outputs for easy reading without downloading.  
> **Colab** lets you edit and run the code interactively in the cloud.  
> **Binder** launches a JupyterLab environment in your browser.

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