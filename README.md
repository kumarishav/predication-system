# Multiple Disease Prediction System

This **Multiple Disease Prediction System** predicts the likelihood of **Heart Disease**, **Diabetes**, and **Parkinson's Disease** based on user-provided medical data. Using machine learning algorithms, the system analyzes health parameters to predict the likelihood of these diseases. The project leverages a dataset sourced from Kaggle, containing various health features, and applies algorithms like **Logistic Regression**, **Random Forest**, and **Support Vector Machine (SVM)** to generate predictions.

## Key Features

- **Disease Predictions**: Predicts the likelihood of **Heart Disease**, **Diabetes**, and **Parkinson’s Disease** based on user inputs.
- **User-Friendly Interface**: Allows users to input medical data via an interactive interface, and provides real-time predictions.
- **Machine Learning Algorithms**: The system uses **Logistic Regression**, **Random Forest**, and **SVM** to generate predictions.
- **Data Visualizations**: Provides visual insights into the prediction results and system performance using tools like **Matplotlib** or **Power BI**.
- **Scalable and Flexible**: Can be extended to include additional diseases or different datasets.

## Technologies Used

- **Python**: Core language for implementing machine learning models and handling data preprocessing.
- **Pandas & NumPy**: For data manipulation and processing.
- **Machine Learning**: Algorithms like **Logistic Regression**, **Random Forest**, and **SVM**.
- **Streamlit**: For building an interactive web app to allow users to input their health data and receive predictions.
- **Power BI/Matplotlib**: For creating visualizations to help users understand disease trends and model accuracy.

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/multiple-disease-prediction.git
   cd multiple-disease-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it in the project directory.

4. Run the Streamlit app to interact with the system:
   ```bash
   streamlit run app.py
   ```


## How It Works

1. **Data Collection**: The dataset is loaded from the Kaggle sources and preprocessed using **Pandas** to handle missing values, outliers, and normalization.
2. **Model Training**: Various machine learning models, such as **Logistic Regression**, **Random Forest**, and **SVM**, are trained to predict the likelihood of **Heart Disease**, **Diabetes**, and **Parkinson's Disease** based on the health data.
3. **Prediction**: The system uses the trained model to predict the likelihood of these diseases when a user inputs their medical data.
4. **Real-time Interaction**: The system provides real-time disease predictions via an easy-to-use **Streamlit** interface.

## Use Cases

- **Healthcare Professionals**: Assist doctors in early diagnosis by providing predictions on potential diseases based on a patient’s medical data.
- **Personal Health Monitoring**: Individuals can input their medical data to check the likelihood of various diseases, helping them take preventive actions.
- **Medical Research**: Researchers can analyze disease prediction patterns and correlations between different health parameters.
