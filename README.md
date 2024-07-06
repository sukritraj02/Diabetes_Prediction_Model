# Diabetes Prediction App

This repository contains a Streamlit application that predicts whether a patient is diabetic or not based on their medical data. The application uses a RandomForestClassifier from scikit-learn for the prediction model.

## Table of Contents
- [Diabetes Prediction App](#diabetes-prediction-app)
  - [Table of Contents](#table-of-contents)
  - [Demo](#demo)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Features](#features)
  - [Dependencies](#dependencies)
  - [Contributing](#contributing)

## Demo
A live demo of the application can be found [here](https://www.linkedin.com/feed/update/urn:li:activity:7215397057660874753/).

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/sukritraj02/diabetes_prediction.git
    cd diabetes_prediction
    ```

2. **Create and activate a virtual environment** (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```



## Usage

To run the Streamlit app, execute the following command in your terminal:

```sh
streamlit run app.py
```
This will start a local web server. Open your web browser and go to http://localhost:8501 to interact with the app.

**Features
Patient Data Input: Allows users to input various medical parameters through sliders in the sidebar.
Prediction: Predicts whether the patient is diabetic or not based on the input data.
Visualization: Provides various visualizations comparing the patient's data with the training dataset.

**Dependencies
streamlit
pandas
numpy
scikit-learn
seaborn
matplotlib
plotly
These dependencies are listed in the requirements.txt file and can be installed using the pip install -r requirements.txt command.

**Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
