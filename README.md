# 🌾 Soil–Crop Classification: End-to-End Supervised ML Pipeline

This project demonstrates a complete machine learning workflow for predicting the most suitable crop based on soil attributes. The notebook highlights core data science skills, including exploratory analysis, preprocessing, model training, evaluation, artifact generation, and SQL querying.

---

## 📌 Objective

Soil nutrient composition significantly impacts agricultural yield. Each crop type thrives under specific nutrient ranges and pH conditions.
This project applies supervised multiclass classification to recommend a crop based on measured soil chemistry.

---

## 🧪 Dataset

The notebook loads a dataset with the following numeric features:

| Feature | Description                    |
| ------- | ------------------------------ |
| `N`     | Nitrogen content               |
| `P`     | Phosphorus content             |
| `K`     | Potassium content              |
| `ph`    | Soil acidity/alkalinity        |
| `crop`  | Target crop label (multiclass) |

All analysis and preprocessing occur within the notebook.

---

## 🧠 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Feature scaling and transformation
* Multiclass classification modeling
* Hyperparameter tuning with cross-validation
* Performance evaluation using balanced metrics
* Creation and storage of evaluation artifacts
* Basic SQL querying within Python

These workflow components reflect practical skills relevant to data science and early-stage ML engineering roles.

---

## 🔍 Exploratory Data Analysis

The notebook includes:

* `.info()` and `.describe()` summaries
* Missing value checks
* Class distribution visualization
* Correlation heatmap for numeric features

This provides initial insight into structure and feature relationships.

---

## ⚙️ Preprocessing

A scikit-learn pipeline is used to:

* identify numeric features
* standardize input values
* ensure consistent transformation during training

This supports a clean and reproducible workflow.

---

## ⚡ End-to-End Training Function

A single function (`run_full_pipeline`) performs:

1. Data splitting
2. Hyperparameter tuning
3. Model training
4. Evaluation
5. Artifact generation

Automating these steps encourages reproducibility and streamlined experimentation.

---

## 📏 Model Evaluation

Evaluation focuses on:

* **Balanced Accuracy**
* **Macro-F1**

These metrics help assess performance across unevenly represented crop classes.

A confusion matrix visualizes per-class performance, while a learning curve illustrates model behavior relative to training size.

---

## 📁 Artifacts Saved

The notebook creates an `artifacts/` directory (ml_outputs) containing:

* `summary.json` (evaluation metrics)
* `confusion_matrix.png`
* `learning_curve.png`
* `classification_report.txt`
* `best_model.joblib`

These enable result review without re-running training.

---

## 🗄️ SQL Add-On (Analyst Demonstration)

An in-memory SQLite database is used to demonstrate:

* table creation from a pandas DataFrame
* basic filtering and aggregation
* SQL syntax familiarity

This provides an additional common data workflow component.

---

## 🏗️ Tech Stack

* Python
* Pandas, NumPy
* scikit-learn
* Matplotlib, Seaborn
* SQLite3
* JSON

All execution occurs within the notebook environment.

---

## 🚀 How to Run

1. Clone or download the repository.
2. Open the notebook in Jupyter.
3. Run all cells from top to bottom.

Artifacts will be generated automatically in the `artifacts/` directory.

---

## 📚 Results Insight

The notebook discusses:

* metric interpretation
* class-level performance trends
* model reliability considerations

These points help contextualize the results beyond raw scores.

---

## 🔮 Potential Future Enhancements (not implemented)

* Interpretability via SHAP values
* Comparison to alternative model families
* Simple deployment via a web interface

These improvements can extend model usability and insight depth.

---

## 👤 Author

**Chinwendu Nancy Anabaraonye**
Data Scientist / Computational scientist


