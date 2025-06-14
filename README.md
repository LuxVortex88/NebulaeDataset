# 🌌 Galactic Data Visualization in Python

This project creates a synthetic dataset representing cosmic-scale variables (Nebulae, Andromeda, Milky Way, and Black Holes) and visualizes them using a scatter plot.

## ✨ What This Shows

- Use of `pandas` and `numpy` for creating synthetic datasets
- Basic data visualization with `matplotlib`
- A creative and educational bridge between **space concepts** and **data science**

## 🧪 Dataset

The dataset simulates 500 data points across 4 cosmic features:

```python
data = pd.DataFrame({
    'Nebulae': np.random.rand(500),
    'Andromeda': np.random.rand(500) * 2 + 28,
    'Milky Way': np.random.rand(500) * 2 + 34,
    'Black Holes': np.random.rand(500) * 2 + 40
})

