# Brain Tumor MRI Classification

An experimental project exploring brain MRI image classification with a Jupyter notebook and a Flask interface.

## Project files

- `brain_tumour_detection_using_deep_learning.ipynb` — project notebook
- `main.py` — Flask application and prediction code
- `index.html` — interface template

The prediction code is set up for four labels: pituitary, glioma, no tumor, and meningioma.

## Current setup notes

This repository does not currently include the trained model file expected at `models/model.h5`. Also, `main.py` looks for the HTML template at `templates/index.html`, while `index.html` is currently in the repository root. These need to be addressed before the Flask app can run as written.

## Disclaimer

This is an experimental software project, not a medical device. Its predictions are not medical advice and should not be used for diagnosis or treatment.
