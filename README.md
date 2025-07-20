# 🧬 Diabetes Classification using Decision Tree

This project implements a **Decision Tree Classifier** to predict the presence of diabetes based on medical diagnostic measurements. The model is trained and evaluated using the `diabetes.csv` dataset.

## 📁 Dataset

The dataset (`diabetes.csv`) includes the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 = No diabetes, 1 = Diabetes)

## 🧠 Model

We use the **Decision Tree Classifier** from `scikit-learn` to classify individuals as diabetic or non-diabetic.

## 🔧 Installation

```bash
git clone https://github.com/your-username/diabetes-decision-tree.git
cd diabetes-decision-tree
pip install -r requirements.txt
```

## 📦 Requirements

```
pandas
numpy
scikit-learn
matplotlib
seaborn
```

To install all dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

### 1. Run the training script:

```bash
python train_decision_tree.py
```

### 2. Output

The script performs the following:

- Loads the dataset
- Splits the data into training and test sets
- Trains a decision tree classifier
- Evaluates model accuracy
- Displays the confusion matrix and classification report
- Visualizes the decision tree

## 📊 Sample Results

- **Accuracy:** ~70-80% (depending on the random split)
- **Confusion Matrix**
- **Decision Tree Plot**

## 📈 Visualization

The trained decision tree is visualized using `matplotlib`.

## 🧪 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score

## 📝 License

This project is licensed under the MIT License.

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
