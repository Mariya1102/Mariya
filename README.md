# Housing Price Analysis

A Streamlit web application for analyzing housing prices and their relationships with various features.

## Features

- Upload and analyze housing price data
- Interactive visualizations:
  - Price distribution by furnishing status
  - Price distribution by number of bedrooms
  - Price vs Area scatter plots
  - Price range distribution
  - Feature correlation heatmap

## Setup

1. Install the required packages:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
streamlit run app.py
```

## Data Format

The application expects a CSV file with the following columns:
- price
- area
- bedrooms
- bathrooms
- stories
- mainroad
- guestroom
- basement
- hotwaterheating
- airconditioning
- parking
- prefarea
- furnishingstatus

## Author
24MDS014 