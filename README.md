# 📊 Python & Math for Data Science  

## 📝 Project Overview  
This project focuses on applying **Python, NumPy, Pandas, and Matplotlib** for data manipulation, statistics, and linear algebra operations. It is designed to build a strong mathematical foundation for Data Science.  

## 📌 Key Features  
✅ **Calculate Mean, Median, and Standard Deviation** using NumPy  
✅ **Generate & Visualize a Normal Distribution** (1000 random values)  
✅ **Perform Matrix Multiplication** using NumPy  
✅ **Compute Eigenvalues & Eigenvectors** of a matrix  

## 📂 Files in the Repository  
- **Python-Math-Data-Science.ipynb** → Jupyter Notebook with full implementation  
- **dataset.csv** (if needed) → Sample dataset for analysis  
- **README.md** → Documentation file  

## 📊 Project Implementation  
### 🔹 1. Calculate Mean, Median, and Standard Deviation  
```python
import numpy as np

def calculate_statistics(data):
    mean_value = np.mean(data)
    median_value = np.median(data)
    std_dev = np.std(data)
    return mean_value, median_value, std_dev

