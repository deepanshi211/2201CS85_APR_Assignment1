# APR Assignment 1

This repository contains my **Assignment 1** submission for the course **CS502 -APR (Advanced Pattern Recognition)**.  

---

## 🗃️ Dataset

The dataset used is the *Mall Customers* dataset, taken from [Kaggle](https://www.kaggle.com/datasets/noyeemhossain135/mall-customers-dataset/data).  

---

## 📂 Contents

- `APR_ASSIGNMENT1.ipynb` → Jupyter Notebook with all solutions and explanations.  
- `mall customers.csv` → Dataset used in the assignment.  

---

## 🔍 What’s done in the Notebook (Brief Summary)

1. **Loading & Exploration**  
   - Loaded the dataset `mall customers.csv`.  
   - Displayed dataset dimensions and first 5 rows.  

2. **Preprocessing**  
   - Converted categorical feature `Gender` into numeric values.  
   - Defined features: Gender, Age, Annual Income, and Spending Score.  
   - Created a new target variable `Segment` by categorizing Spending Score into Low, Medium, and High.  

3. **Train-Test Split & Scaling**  
   - Split dataset into training (70%) and testing (30%).  
   - Scaled features using StandardScaler for better model performance.  

4. **Model Implementation (KNN)**  
   - Implemented **K-Nearest Neighbors** classifier (`k=5`).  
   - Trained the model on training data.  
   - Predicted customer segments for test data.  

5. **Evaluation**  
   - Generated Confusion Matrix, Classification Report, and Accuracy Score to measure performance.  

6. **Visualization**  
   - Plotted scatter graph of Annual Income vs Spending Score, colored by segment (Low, Medium, High).  


---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/username/2201CS85_APR_Assignment1.git
   cd 2201CS85_APR_Assignment1
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook APR_ASSIGNMENT1.ipynb
   ```
3. Run the cells in order to see the outputs.

---

## 👤 Author

- **Deepanshi Verma** (2201CS85)  
- B.Tech, Computer Science and Engineering  
- IIT Patna  

---
