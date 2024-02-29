# diabetes_prediction_web_app_using_streamlit
This repository contains code of a streamlit web application for diabetes prediction.

## App Preview
https://github.com/umairsiddique3171/diabetes_prediction_web_app_using_streamlit/assets/148565997/3a92b058-f609-4177-a9cd-a4f492da5315

## Diabetes Classifier
Training diabetes classifier involved training different Machine Learning models using GridSearchCV for classifying diabetic and non-diabetic patients based on medical tests data. Several Preprocessing techniques were applied to the data such as EDA, normalization, etc. You can access the classifier source code [here](https://github.com/umairsiddique3171/Machine-Learning-Projects/tree/main/diabetes_prediction).

## App Features

- **Input Form**: In web application interface, user has to fill following fields : pregnancies,glucose,blood_pressure,skin_thickness,insulin,bmi,dpf and age.
- **Prediction**: After filling required fields, use has to push the result button to get the classification results with confidence score.

## Technologies Used

- Python
- Streamlit
- Scikit-learn

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/umairsiddique3171/diabetes_prediction_web_app_using_streamlit.git
    cd diabetes_prediction_web_app_using_streamlit
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv env
    .\env\Scripts\activate
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

5. Access the app in your browser at returned local host (e.g. `http://localhost:8501`).


