Sure buddy! Here's a **simpler version** of the `README.md` for your crop yield prediction project:

---

## 🌾 Crop Yield Prediction

This project predicts crop yield based on temperature, rainfall, pesticide usage, year, and crop type using machine learning.

---

### 📁 Dataset

The dataset contains:

* Area (country)
* Crop type (Item)
* Year
* Average rainfall (mm)
* Pesticides used (tonnes)
* Average temperature (°C)
* Yield (hg/ha) → **Target**

---

### 🔧 Tools Used

* Python
* Pandas & NumPy
* Scikit-learn
* Jupyter Notebook

---

### 🧠 ML Model

* Used: **Decision Tree Regressor**
* Data Preprocessing:

  * OneHotEncoder for `Area`, `Item`
  * StandardScaler for numeric features

---

### 🚀 How to Run

1. Open `CropYield.ipynb` in Jupyter Notebook
2. Run all cells
3. Use the `prediction()` function to test your own values

---

### 📦 Example Prediction

```python
result = prediction(1990, 1485.0, 121.0, 16.37, 'Albania', 'Maize')
print(result)
```

---

Let me know if you want this as a downloadable `.md` file!
