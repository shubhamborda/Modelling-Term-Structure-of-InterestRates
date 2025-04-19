
# Modelling-Term-Structure-of-InterestRates

This project explores interpolation techniques to estimate missing interest rates across different tenors in the US Treasury yield curve.

## 🔧 Techniques Used

- **Linear Interpolation**: Straight-line estimation between two points.
- **Polynomial Interpolation**: Smooth curve fitting using multiple points (e.g., quadratic or cubic).
- **Day Count Convention**: Assumes a 30/360 convention for mapping tenor to days (e.g., 1 Yr = 360, 6 Mo = 180).

## 📊 Visualizations

- Plots include known rates, interpolated values, and missing data markers.
- Annotations and lines highlight key estimated points.

## 🛠️ Tools

- `pandas`, `numpy`, `matplotlib`
- Interpolation via `numpy.polyfit` and `pandas.interpolate(method='polynomial')`

## 📁 Contents

- `yield_analysis.ipynb`: Code for curve modeling and visualization.
- `dayCountMapping`: Tenor-to-day mapping based on 30/360 convention.

---

**Author**: Shubham Borda | **Year**: 2025
