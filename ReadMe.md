# Real Estate Price Prediction App

This repository contains a Streamlit application for predicting housing prices using a trained Random Forest model and a custom preprocessing pipeline.
Have a try at this link: https://ca-houseprice-rf-app-czxy7psynandypzc3ejftu.streamlit.app/

## Setup Instructions

1. Install required packages:

```
pip install -r requirements.txt
```

2. Run the training script to generate model files:

```
python train_model.py
```

This will create the following files in the current directory:
- model.pkl
- preprocessor.pkl
- price_bounds.pkl

3. Launch the Streamlit app:

```
streamlit run app.py
```

## File Structure

- app.py: Main Streamlit app
- train_model.py: Generates the model and preprocessor
- preprocessing.py: Preprocessing pipeline class
- requirements.txt: Python package dependencies


## Note:
This app gives housing price predictions based on past data and a trained model — it's pretty smart, but not psychic 😉. So please don’t take the results too seriously, and definitely don’t use them to buy or sell a house!
