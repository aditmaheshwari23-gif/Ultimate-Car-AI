# Car AI Assistant (Jupyter Notebook Project)

## Overview

This project is an interactive Car Data Analysis and AI-style assistant built using Python in a Jupyter Notebook. It allows users to explore, filter, search, and compare cars using natural language-style input.

The system works like a mini intelligent search engine for car datasets, supporting queries such as brand search, price filtering, fuel filtering, and brand comparisons.

## Features

- Search cars by brand name
- Filter cars by price range
- Identify cheapest and most expensive cars
- Filter by fuel type (diesel, petrol)
- Compare two car brands (e.g., Toyota vs Honda)
- Natural language-style query support
- Real-time dataset insights (average price, total results)

## Dataset Requirements

The project requires a CSV file named cars.csv with the following columns:

- brand
- km_driven
- fuel
- selling_price

The file must be placed in the same folder as the notebook.

## Installation

Install required dependencies:

pip install pandas

Optional (for graphs if you extend the project):

pip install matplotlib

## How to Run

1. Open Jupyter Notebook
2. Place cars.csv in the same folder as the notebook
3. Run the notebook cell containing the AI assistant code
4. Enter queries in the input prompt and interact with the system

## Example Queries

toyota cars  
bmw under 5000000  
diesel cars  
cheap cars  
toyota vs honda  
expensive cars  

## Project Structure

project-folder/
├── cars.csv
├── Car_AI_Assistant.ipynb
└── README.md

## Notes

- The program runs in a continuous loop until "exit" is entered
- All processing is done locally using Pandas
- Ensure dataset column names are correct

## Future Improvements

- Machine learning-based price prediction
- Improved natural language understanding
- Advanced recommendation system
- Web-based dashboard using Streamlit or Flask

## Author

Adit Maheshwari
