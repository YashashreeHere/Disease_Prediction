# Disease Prediction System using Machine Learning
A predictive analytics tool that identifies potential diseases based on user-reported symptoms using supervised learning.

## Overview
This project utilizes the **Kaggle Disease Symptom Dataset** to map various symptoms to medical conditions. By comparing multiple algorithms (Random Forest, Decision Tree, and KNN), the system provides high-accuracy predictions along with probability scores.

## Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **Environment:** Google Colab / Jupyter Notebook

## Dataset
The dataset contains 4,900+ records of patients with 41 different diseases. Each record consists of a list of symptoms (e.g., muscle wasting, patches in throat, high fever).
[Dataset Link](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset)

## Model Performance
| Algorithm | Accuracy |
| :--- | :--- |
| Random Forest | ~99% |
| Decision Tree | ~95% |
| KNN | ~92% |

## How to Run
1. Clone the repo.
2. Open `disease_prediction.ipynb` in Google Colab.
3. Upload `dataset.csv`.
4. Run all cells to train models and see the prediction interface.
