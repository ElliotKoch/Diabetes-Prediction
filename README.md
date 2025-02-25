# Diabetes Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict whether a patient has diabetes based on a medical dataset using various machine learning techniques. The dataset contains patient medical records, and the model applies supervised learning methods, including deep learning, to make accurate predictions. 

## 📂 Repository Structure
```
Diabetes-Prediction/
│── Koch_Elliot_Predict_Diabetes_Presentation.pdf  # Project Presentation
│── Koch_Elliot_Predict_Diabetes_Report.pdf        # Final Report
│── Koch_Elliot_Predict_Diabetes.ipynb            # Jupyter Notebook with ML model
│── README.md                                      # Project documentation
│
├── Datasets/
│   ├── data.csv                                   # Main dataset
│   ├── mapping.csv                                # Additional data mapping
```

## 📊 Dataset
The dataset consists of medical records with around 50 features, including patient demographics, medical history, and diabetes indicators.

- **Data Source**: Processed from medical datasets
- **Features**:
  - Patient demographics (age, gender, ethnicity)
  - Medical indicators (glucose level, insulin usage, etc.)
  - Diabetes classification (diabetic/non-diabetic)

## ⚙️ Installation & Setup
To run the project, follow these steps with python version 3.11.9:

1. **Clone the repository**
   ```sh
   git clone https://github.com/ElliotKoch/diabetes-prediction.git
   cd diabetes-prediction
   ```
3. **Setup virtual environment**
   ```sh
   python -m venv .venv
   .venv\Scripts\activate
   where python
   ```
3. **Install dependencies**
   ```sh
   python.exe -m pip install --upgrade pip
   pip install -r requirements.txt
   ```
4. **Run the jupyter notebook**
   ```sh
   jupyter notebook Koch_Elliot_Predict__Diabetes.ipynb
   ```
5. **Close the virtual environment** 
   ```sh
   deactivate
   ```

## 🧠 Model Training
The project applies multiple machine learning techniques:
- **Supervised Learning**: Linear Regression, Random Forest, SVM, Decision Tree, Gradient Boosting Machine (GBM)
- **Unsupervised Learning**: K-Means Clustering
- **Deep Learning**: A neural network with hyperparameter tuning using Keras

### 🏆 Model Performance
| Model | Accuracy |
|--------|---------|
| Basic Neural Network | 99.6% |
| Optimized Deep Learning | 99.87% |

## 🚀 Usage
After running the notebook, the trained model can be used for predictions. On a different Python file, the best model can be loaded with:
```sh
   loaded_model = tf.keras.models.load_model("dl_model.h5")
```

## 📜 License
This project is open-source and free to use for research and educational purposes.

## 📧 Contact
For any inquiries, contact **Elliot Koch** at [kochelliotpro@gmail.com].

