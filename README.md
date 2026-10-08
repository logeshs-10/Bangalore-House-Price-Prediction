# House Price Prediction Web Application

A web application that predicts house prices in Bengaluru based on location, BHK, area (sq. ft.), and number of bathrooms. Built using Python, Machine Learning, and Flask.

## Features

- Predicts house prices from user inputs
- Inputs: location, BHK, area (sq. ft.), and bathrooms
- Trained on the Bengaluru House Data dataset
- Data processing with Pandas and NumPy
- Flask backend serving the trained model through a REST API
- Frontend built with HTML, CSS, and JavaScript (jQuery)

## Tech Stack

- Python
- Flask
- Machine Learning
- Pandas, NumPy
- HTML, CSS, JavaScript

## Project Structure

```
project
├── Client
│   ├── app.html
│   ├── app.css
│   ├── app.js
│   └── image.png
├── Model
│   ├── main.ipynb
│   └── Bengaluru_House_Data.csv
└── Server
    ├── server.py
    ├── util.py
    ├── columns.json
    └── bangalore_house_model.pickel
```

## API Endpoints

- `GET /get_location_names` returns the list of available locations
- `POST /predict_home_price` returns the estimated price (in Lakh) for the given location, area, BHK, and bathrooms
