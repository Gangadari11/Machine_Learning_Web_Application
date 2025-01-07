# Machine_Learning_Web_Application

A web application that predicts software developer salaries based on user input, leveraging Python, Streamlit, and a Machine Learning model.

### 🎯 Overview
This application allows users to:

Predict software developer salaries by selecting their country, education level, and years of experience.
Explore trends in developer salaries using data visualization from the Stack Overflow Developer Survey 2020.

### 🛠️ Technologies Used
* Python: The core programming language used for data processing and model implementation.
* Streamlit: A lightweight framework for building interactive web applications.
* Machine Learning: A regression model trained on survey data to estimate salaries.


### 🚀 Features
1. Salary Prediction:

* Predicts estimated salary using a pre-trained regression model.
* User-friendly interface to input details like country, education, and experience.
2. Data Exploration:

* Visualizes country-wise and experience-wise salary trends.
* Pie charts, bar charts, and line charts for interactive data exploration.
Interactive UI:

* Sidebar for easy navigation between "Predict" and "Explore" pages.
* Responsive sliders and dropdowns for inputs.

### 🖥️ How to Run the App
1. Clone this repository:
```bash
git clone https://github.com/Gangadari11/Machine_Learning_Web_Application.git
cd repo-name
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the app using Streamlit:
```bash
streamlit run app.py
```
4. Open the app in your browser at http://localhost:8501.

### 💡 Highlights
* The Machine Learning Model predicts salaries with features like country, education, and experience.
* Built with Streamlit, making it simple to create interactive and visually appealing web apps.
* Powered by Python libraries like numpy, pandas, matplotlib, and pickle.

### 📊 Dataset
This app is built on data from the Stack Overflow Developer Survey 2020. The data has been cleaned and preprocessed for training the regression model.
