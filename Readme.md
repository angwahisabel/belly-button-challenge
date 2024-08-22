# Belly Button Biodiversity Dashboard

This project visualizes data from the Belly Button Biodiversity dataset, enabling users to explore bacterial cultures found in human belly buttons. The interactive dashboard includes a dropdown menu, a demographic info panel, and charts displaying the top 10 bacterial cultures.

## Project Structure

├── index.html
├── static
│ ├── js
│ │ └── app.js
│ └── css
│ └── style.css
└── README.md

## Features

- **Dropdown Menu:** Select test subject IDs to view specific data.
- **Demographic Info Panel:** Displays metadata for the selected subject.
- **Bar Chart:** Shows the top 10 bacterial cultures found in the selected subject.
- **Bubble Chart:** Visualizes bacterial cultures with marker size and color representing quantity and type.

## Setup and Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/angwahisabel/belly-button-challenge.git
   cd belly-button-challenge

   npm install -g live-server
   live-server

- **View the Dashboard in your web browser**

http://127.0.0.1:5500/belly-button-challenge/Starter_Code/index.html

## Data Source

Data is fetched from samples.json.

## Technologies Used

- **HTML5, CSS3, JavaScript**
- **D3.js for data visualization**
- **Plotly.js for interactive charts**