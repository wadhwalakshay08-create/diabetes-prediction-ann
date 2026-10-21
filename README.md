# 🧠 Diabetes Prediction Using Deep Learning

My **first Deep Learning project** — an Artificial Neural Network (ANN) built using TensorFlow and Keras to predict the likelihood of diabetes based on health-related features.

This project helped me understand the practical implementation of Deep Learning, from data preprocessing and feature scaling to model training and evaluation.

## 🚀 Project Overview

The goal of this project is to build a binary classification model that predicts whether a person is likely to have diabetes based on input features from a diabetes dataset.

The model uses an Artificial Neural Network (ANN) with multiple hidden layers, ReLU activation, Batch Normalization, Dropout, and a Sigmoid output layer.

## 🛠️ Technologies Used

- **Python** — Programming language
- **TensorFlow & Keras** — Deep Learning model
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Scikit-learn** — Data preprocessing and evaluation
- **Matplotlib** — Data visualization
- **Jupyter Notebook / VS Code** — Development environment

## 🏗️ Model Architecture

The ANN architecture includes:

- Input layer based on the number of features
- Dense layer with 512 neurons and ReLU activation
- Batch Normalization and Dropout
- Dense layer with 256 neurons and ReLU activation
- Batch Normalization and Dropout
- Dense layer with 128 neurons and ReLU activation
- Dropout regularization
- Dense layer with 64 neurons and ReLU activation
- Output layer with 1 neuron and Sigmoid activation

### Training Configuration

- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy
- Maximum Epochs: 100
- Batch Size: 32
- Early Stopping: Used to help reduce overfitting

## 🔄 Project Workflow

1. Load and explore the dataset.
2. Perform data preprocessing.
3. Separate input features and target variable.
4. Split the data into training and testing sets.
5. Scale the input features.
6. Build and compile the ANN model.
7. Train the model using EarlyStopping.
8. Evaluate model performance on test data.
9. Visualize training and validation performance.

## 📊 Model Evaluation

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual evaluation results should be recorded after running the final version of the notebook.

## 📂 Project Structure

```text
diabetes-prediction-ann/
│
├── diabetes_prediction.ipynb
├── diabetes_prediction_dataset.csv
├── requirements.txt
└── README.md
```

*Update the filenames above to match the files in your repository.*

## ⚙️ Installation and Usage

**1. Clone the repository**

```bash
git clone https://github.com/wadhwalakshay08-create/diabetes-prediction-ann.git
```

**2. Navigate to the project directory**

```bash
cd diabetes-prediction-ann
```

**3. Create and activate a virtual environment (optional)**

```bash
python -m venv venv
```

Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

**4. Install dependencies**

```bash
pip install -r requirements.txt
```

**5. Run the notebook**

Open `diabetes_prediction.ipynb` in VS Code or Jupyter Notebook and run the cells in order.

## 📚 Key Learnings

- Building an Artificial Neural Network using TensorFlow/Keras
- Understanding hidden layers and activation functions
- Applying feature scaling to training data
- Using Dropout and Batch Normalization
- Implementing EarlyStopping
- Evaluating a classification model
- Managing a project using Git and GitHub

## 🔮 Future Improvements

- Hyperparameter tuning
- Comparing different ANN architectures
- Improving evaluation and handling class imbalance where needed
- Building a simple web interface for predictions
- Deploying the model as a demonstration application

## ⚠️ Disclaimer

This project is intended for **educational purposes only**. It is not a medical diagnostic tool and should not be used to make healthcare decisions.

## 👨‍💻 Author

**Lakshay Wadhwa**

GitHub: [@wadhwalakshay08-create](https://github.com/wadhwalakshay08-create)

---

⭐ If you find this project interesting, feel free to explore the repository and share suggestions!
