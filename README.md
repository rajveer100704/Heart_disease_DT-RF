# 🌳 Decision Trees & Random Forests - Heart Disease Classification

## 📌 Objective
The goal of this task is to **learn tree-based models** for classification using the **Heart Disease dataset**.  
We implement **Decision Trees** and **Random Forests**, visualize results, analyze overfitting, and interpret feature importance.

---

## 📂 Files in this Repo
- `data/heart.csv` → dataset  
- `decision_tree_rf.py` → main Python script  
- `notebook.ipynb` → Jupyter notebook version  
- `outputs/decision_tree.png` → visualization of decision tree  
- `outputs/feature_importance.png` → feature importance plot  
- `README.md` → explanation  

---

## ⚙️ Steps Performed
1. **Load Dataset** – Heart Disease dataset (`heart.csv`).  
2. **Decision Tree Classifier** – trained and visualized using `matplotlib` & `graphviz`.  
3. **Overfitting Check** – compared full tree vs. limited depth (`max_depth=4`).  
4. **Random Forest Classifier** – trained with 100 trees, accuracy compared with single decision tree.  
5. **Feature Importances** – plotted using `sns.barplot`.  
6. **Cross Validation** – evaluated using `cross_val_score`.  

---

## 📊 Results
- **Decision Tree Accuracy**: ~98%  
- **Decision Tree (max_depth=4)**: ~80%  
- **Random Forest Accuracy**: ~98.5%  
- **Cross-Validation Mean Accuracy**: ~99%  

Random Forest outperformed a single Decision Tree due to **bagging** and **reduced overfitting**.

---

## 🛠️ Tools Used
- `Python 3`  
- `Scikit-learn`  
- `Matplotlib` & `Seaborn`  
- `Graphviz` (optional for better tree plots)  

---

## 🚀 How to Run
```bash
# Clone the repo
git clone https://github.com/rajveer100704/Heart_disease_DT-RF.git
cd DecisionTrees_RandomForest

# Install dependencies
pip install -r requirements.txt

# Run Python script
python Heart_Diseases.py
