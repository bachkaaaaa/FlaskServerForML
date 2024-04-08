# Health Monitor Project - Machine Learning Part

This repository contains the machine learning component of the Health Monitor project, which aims to predict the presence or absence of heart disease based on various patient attributes.

## Dataset Information

The dataset used for this project contains the following features:

* Patient Identification Number: Numeric
* Age: Numeric (in years)
* Gender: Binary (0: female, 1: male)
* Resting blood pressure: Numeric (94-200 mm Hg)
* Serum cholesterol: Numeric (126-564 mg/dL)
* Fasting blood sugar: Binary (0: false/ <= 120 mg/dL, 1: true/ > 120 mg/dL)
* Chest pain type: Nominal (0: typical angina, 1: atypical angina, 2: non-anginal pain, 3: asymptomatic)
* Resting electrocardiogram results: Nominal (0: normal, 1: ST-T wave abnormality, 2: probable or definite left ventricular hypertrophy)
* Maximum heart rate achieved: Numeric (71-202)
* Exercise induced angina: Binary (0: no, 1: yes)
* Oldpeak (ST depression induced by exercise relative to rest): Numeric (0-6.2)
* Slope of the peak exercise ST segment: Nominal (1: upsloping, 2: flat, 3: downsloping)
* Number of major vessels: Numeric (0, 1, 2, 3)
* Classification (target): Binary (0: absence of heart disease, 1: presence of heart disease)

## Algorithms Used

The following machine learning algorithm was employed for heart disease prediction:

* Random Forest Classifier

# Flask Server for Machine Learning Model

This repository contains a Flask server setup for deploying a machine learning model. The server exposes endpoints to interact with the model through HTTP requests.

## Prerequisites

Before running this application, ensure you have the following installed:

- Python (3.6 or higher)
- Flask (to install it: $ pip install flask)

## Setup

1. **Clone the repository:**

    ```
    git clone <repository_url>
    ```

2. **Navigate to the project directory:**

    ```
    cd ml_server
    ```
3. **Configure Flask server:**

    - Update `main.py` with necessary endpoint logic .
    - Ensure correct port configuration and any other server settings.

## Usage

1. **Run the Flask server:**

    ```
    python main.py
    ```

2. **Interact with the API:**

    - Send HTTP requests to the endpoints exposed by the Flask server.
    - Example: `GET http://localhost:5000/predict?input=<your_input_data>`

## Endpoints

- `/predict`: Endpoint to make predictions using the deployed model.
- Add additional endpoints as needed for your application.

## Contributing

Contributions are welcome! If you find any issues or improvements, feel free to open an issue or submit a pull request.



  
