#  Task 6: K-Nearest Neighbors (KNN) Classification — Iris Dataset

##  Objective

Implement the **KNN algorithm** for classification problems and understand the concepts of **instance-based learning**, **distance metrics**, and **K selection**.



##  Dataset

**Iris Dataset**

* Features: Sepal Length, Sepal Width, Petal Length, Petal Width
* Target: Species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`)



##  Tools & Libraries

* **Python 3.x**
* **Pandas** – Data handling
* **NumPy** – Numerical operations
* **Matplotlib** – Visualization
* **Scikit-learn** – Model building, preprocessing, evaluation



##  Steps Implemented

1. **Load & Explore Data** – Checked dataset structure and features.
2. **Feature Normalization** – Used `StandardScaler` to standardize feature values (important for KNN).
3. **Train-Test Split** – 80% training, 20% testing.
4. **K Value Experimentation** – Tested `k` from 1 to 10, plotted accuracy vs K.
5. **Model Evaluation** – Accuracy, confusion matrix, classification report.
6. **Decision Boundary Visualization** – Plotted using first two features for 2D representation (with `LabelEncoder` to avoid errors).



##  Results

* **Best K Value:** *varies depending on train/test split* (e.g., K=6 in my run).
* **Accuracy:** \~96–100% on test data.
* **Confusion Matrix:** Shows correct classification for most/all samples.
* **Decision Boundary Plot:** Clear separation of species in 2D space.



##  How to Run

```bash
pip install pandas numpy matplotlib scikit-learn
jupyter notebook Task_6.ipynb

##  Author

**Kasara Pavan Sai Reddy**
B.Tech – Artificial Intelligence & Machine Learning
Presidency University, Bengaluru

