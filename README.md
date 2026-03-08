# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning techniques based on various housing features such as area, number of rooms, and other property-related attributes.
The goal is to build a model that can estimate the price of a house accurately using historical housing data.

This project demonstrates the complete **Machine Learning workflow**, including data preprocessing, feature engineering, model training, and evaluation.

---

# 🚀 Features

* Data preprocessing and cleaning
* Handling missing values
* Feature engineering
* Train-test data splitting
* Machine Learning model training
* Model evaluation and prediction

---

# 🛠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

# 📂 Project Structure

```
House-Price-Prediction/
│
├── house_price_prediction.ipynb   # Jupyter Notebook with full ML workflow
├── dataset.csv                    # Housing dataset                 # Project documentation
```

---

# 📊 Machine Learning Workflow

### 1️⃣ Data Collection

The dataset contains housing-related information such as:

* Median income
* Housing median age
* Total rooms
* Population
* Households
* Location data

---

### 2️⃣ Data Preprocessing

Steps performed:

* Handling missing values using **SimpleImputer**
* Feature scaling
* Data transformation
* Encoding categorical features

---

### 3️⃣ Data Splitting

The dataset is split into:

* **Training set (80%)**
* **Testing set (20%)**

---

### 4️⃣ Model Training

Machine Learning models are trained using **Scikit-learn** to predict housing prices.

Example:

```python
from sklearn.model_selection import train_test_split

train_set, test_set = train_test_split(data, test_size=0.2, random_state=42)
```

---

### 5️⃣ Model Evaluation

Model performance is evaluated using metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

# 📈 Example Prediction

Input:

```
Area: 1500 sq ft
Bedrooms: 3
Bathrooms: 2
```

Predicted Output:

```
Estimated Price: ₹82,50,000
```

---

# ▶️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/Sumeru24/House-Price-Prediction.git
```

### 2️⃣ Navigate to the project folder

```
cd house-price-prediction
```

### 3️⃣ Install dependencies

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 4️⃣ Run the notebook

```
jupyter notebook
```

Open the **house_price_prediction.ipynb** file and run all cells.

---

# 📚 Learning Outcomes

Through this project you will learn:

* Data preprocessing
* Feature engineering
* Machine Learning model training
* Model evaluation
* Real-world ML pipeline development

---

# 🔮 Future Improvements

* Add more advanced ML models
* Hyperparameter tuning
* Deploy the model using **Flask or Streamlit**
* Build a web interface for predictions

---

# 👨‍💻 Author
Sumeru

