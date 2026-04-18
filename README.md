# 📘 WSQ Training Modules

![Status](https://img.shields.io/badge/status-active-success)
![Language](https://img.shields.io/badge/language-python-blue)
![Focus](https://img.shields.io/badge/focus-data%20science%20%7C%20pandas%20%7C%20numpy-orange)

## 🧠 Overview

This repository contains structured training modules from the **Wall Street Quant (WSQ) program**, covering core Python, NumPy, and Pandas concepts with a focus on data analysis and time series.

The material is organized into progressive modules, starting from Python fundamentals and moving toward more advanced data manipulation techniques.

---

## 🎯 Purpose

This repository serves as:

- A **learning archive** of WSQ coursework  
- A **reference library** for key Python and data science concepts  
- A **foundation** for more advanced financial and analytical projects  

---

## 📂 Repository Structure

```plaintext
wsq_training_modules/
│
├── 01_python/
│   ├── homework_01/
│   └── lessons/
│       ├── 01_Variables.ipynb
│       ├── 02_Numbers.ipynb
│       ├── ...
│
├── 02_numpy/
│   └── lessons/
│       ├── 01_NumpyIntro.ipynb
│       ├── 02_ArraysBasicOperations.ipynb
│       ├── ...
│
├── 03_panda_series/
│   └── lessons/
│       ├── 01_Construction.ipynb
│       ├── 02_RetrieveAndModify.ipynb
│       ├── ...
│
├── 04_pandas_dataframe/
├── 04_pandas_df/
│   ├── 01_Construction.ipynb
│   ├── 02_RetrieveAndModify.ipynb
│   ├── ...
│
├── 05_pandas_more/
│   ├── homework/
│   └── lessons/
│       ├── 01_MissingValues.ipynb
│       ├── 02_ReindexingSorting.ipynb
│       ├── ...
│
├── 06_morePandas2Code/
│   ├── data/
│   ├── 01_CategoricalData.ipynb
│   ├── 02_ReadingWritingFiles.ipynb
│   ├── 03_MultiIndexing.ipynb
│   ├── 04_TimeSeries.ipynb
│   ├── 05_GroupbyPivotMerge.ipynb
│   ├── 06_PandasMisc.ipynb
│
├── .gitignore
├── environment.yml
├── environment_custom.yml
```

---

## 🧪 Topics Covered

### 🐍 Python Fundamentals
- Variables, data types, control flow
- Functions and syntax

### 🔢 NumPy
- Arrays and vectorized operations
- Linear algebra basics

### 🐼 Pandas
- Series and DataFrames
- Indexing and alignment
- Missing data handling
- GroupBy and aggregation
- MultiIndex (hierarchical data)
- Time series analysis

---

## ⚙️ Environment Setup

This project includes Conda environment files:

```
environment.yml - This is the reproducible environment
environment_custom.yml - This is a custom build and not a reproducible environment
```

To create the environment:

```bash
conda env create -f environment.yml
conda activate wsq_training
```

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Brice-Dev-Lab/WSQ_Training_Modules.git
   ```

2. Open the notebooks in:
   - DataSpell (recommended)
   - Jupyter Lab
   - VS Code (with Jupyter extension)

3. Work through modules in order:
   ```
   01_python → 02_numpy → 03_pandas_series → ...
   ```

---

## 💡 Notes

- This repository focuses on **conceptual understanding and hands-on practice**
- Some notebooks follow the WSQ curriculum directly, while others may include additional exploration
- The goal is to build a strong foundation for **data science and financial modeling**

---

## 🧭 Future Direction

This repository supports progression into:

- Quantitative finance projects  
- Time series modeling  
- Backend data pipelines  
- Machine learning applications  

---

## ⚠️ Disclaimer

This repository is for educational purposes and training exercises.  
Not intended for production or financial decision-making use.
