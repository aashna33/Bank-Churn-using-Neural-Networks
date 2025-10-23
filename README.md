Bank Churn Prediction using Neural Networks

This project predicts whether a customer is likely to leave (churn) a bank based on their personal and financial details, using an Artificial Neural Network (ANN) built with Tensorflow and Keras.


 Features: 
- Customer churn prediction using deep learning  
- Preprocessing pipeline for numerical and categorical data  
- Trained using TensorFlow (ANN model)  
- Achieved high accuracy and recall on test data  
- Easy-to-run Jupyter notebook / Python script
    

Tech Stack:
- Language: Python  
- Framework: TensorFlow, Keras  
- Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  


Project Structure:
ann/
├── data/ # Dataset 
├── model/ # Saved model or weights
├── notebooks/
├── src/ # Training and preprocessing scripts
├── logs/ # TensorBoard logs (ignored in Git)
└── requirements.txt # Python dependencies

How to Run:

Clone this repository:
git clone https://github.com/aashna33/Bank-Churn-using-Neural-Networks.git
cd Bank-Churn-using-Neural-Networks

Create and activate your virtual environment:
python -m venv tfenv
.\tfenv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Run the model:
python src/train_model.py
OR:
jupyter notebook notebooks/BankChurnANN.ipynb


Credits: Krish Naik.
