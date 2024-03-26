Fake Domain Detector (Beta) - StendhalGPT Security
===================================================

This service helps detect potentially fake domain names. The model is trained on a dataset of 50,000 sites, which represents around 2% of the available data. It's suitable for businesses and also integrated soon into StendhalGPT+. Only available for .fr websites.

Example: 'colis-livraison.fr', 'cnil-info.fr', 'antai-gov.fr', 'amendes-paiement.fr', 'leclerc.fr', 'hachette.fr'.

How to use
----------

1. Enter a domain name.
2. Click the "Predict" button to see the prediction score.
3. The application will display whether the domain is likely to be genuine or fake based on the prediction score.

Requirements
------------

- Python 3.x
- Keras
- TensorFlow
- Streamlit

Installation
------------

1. Clone this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run the application using `streamlit run app.py`.

Data Source
-----------

Afnic, <https://dl.red.flag.domains/> and others

