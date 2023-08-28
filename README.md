
# Disease Diagnosis System using Flask and TensorFlow/Keras

This project implements a web-based disease diagnosis system using Flask and TensorFlow/Keras. Given symptoms as input, the system predicts potential diseases and suggests relevant hospitals.

## Features

- Predicts potential diseases based on symptoms.
- Provides hospital recommendations based on the predicted disease.

## Prerequisites

- Python (version 3.x)
- TensorFlow (version 2.x)
- Flask (version 2.0.1)
- Other dependencies mentioned in `requirements.txt`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

  ## install requirements
   pip install -r requirements.txt

## Run application
python app.py
Open a web browser and navigate to http://localhost:5000 to access the application.

### Usage
1) Visit the home page to get an overview of the project.
2) Navigate to the form page to input your symptoms.
3) Submit the form to get potential disease predictions and hospital recommendations

## Additional Notes
1. The machine learning model is loaded from model.json and model.h5 files.
2. The utils.py module contains utility functions for data conversion.
3. The project's web interface is built using Flask and HTML templates.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or a pull request.
