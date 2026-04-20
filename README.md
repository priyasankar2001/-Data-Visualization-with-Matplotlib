# 📊 Data Visualization with Matplotlib

> A clean, structured walkthrough of Python's most widely used charting library — from first-principles plots to real-world data analysis.

---

## 🗂️ Overview

This notebook covers **8 chart types** with a consistent minimal visual style, reproducible mock data, and annotated code cells. Designed to be both a learning guide and a personal reference.

| # | Chart Type | Description |
|---|-----------|-------------|
| 1 | **Line Plot** | Trends over continuous data |
| 2 | **Subplots** | Multi-panel side-by-side comparisons |
| 3 | **Bar Chart** | Vertical & horizontal category comparisons |
| 4 | **Histogram** | Frequency distribution with mean line |
| 5 | **Pie Chart** | Part-to-whole proportions with explode highlight |
| 6 | **Scatter Plot** | Correlations with colour-mapped third variable |
| 7 | **Box Plot** | Statistical spread across groups |
| 8 | **Real-World Analysis** | Restaurant dataset (mock Zomato-style data) |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557C?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-latest-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-latest-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/matplotlib-visualization.git
cd matplotlib-visualization
```

### 2. Install dependencies
```bash
pip install matplotlib numpy pandas jupyter
```

### 3. Launch the notebook
```bash
jupyter notebook matplotlib_portfolio.ipynb
```

---

## ✨ Design Choices

All charts share a **unified visual theme** configured once at the top of the notebook:

- **White background** with a subtle `#F9F9F9` axes panel
- **Dashed grid lines** in a light grey (`#E0E0E0`) — present but unobtrusive
- **Top & right spines removed** for a cleaner look
- **Muted colour palette** — 10 carefully chosen colours that pair well together
- **Value labels** added to bar charts for immediate readability

```python
PALETTE = [
    "#4878D0", "#EE854A", "#6ACC65", "#D65F5F",
    "#956CB4", "#8C613C", "#DC7EC0", "#82C6E2",
    "#D5BB67", "#797979"
]
```

---

## 📁 File Structure

```
📦 matplotlib-visualization
 ┣ 📓 matplotlib_portfolio.ipynb   ← Main notebook
 ┗ 📄 README.md
```

---

## 📌 Key Concepts Demonstrated

- Using `plt.rcParams.update()` to set a global style once
- Side-by-side comparisons with `plt.subplots()`
- Adding **value annotations** directly to bar charts via `ax.text()`
- Marking statistical reference lines (e.g., mean) with `ax.axvline()`
- Colour-mapping a third variable in scatter plots using `c=` and `cmap=`
- Styling box plots with `patch_artist=True`
- Building **self-contained notebooks** with mock data instead of local files

---

## 🙋 About

Built as a portfolio project to demonstrate practical data visualisation skills using Python.  
All data in this notebook is **synthetically generated** — no external files required.

---

*Feel free to fork, star ⭐, or open an issue if you have suggestions!*
