# Belly Button Biodiversity Dashboard

This project is an interactive data visualization dashboard built with **JavaScript**, **D3.js**, and **Plotly.js**. It explores the diversity of bacterial species found in human belly buttons, using a dataset of biological samples.

## Features

- **Dropdown Selection:** Users can choose different test subject IDs to dynamically update the charts and metadata.
- **Metadata Panel:** Displays demographic information for each test subject.
- **Interactive Bar Chart:** Shows the top 10 bacterial species (OTUs) found in the sample, ordered by the number of bacteria.
- **Interactive Bubble Chart:** Visualizes the entire sample with bacterial species and their frequencies.

## Project Structure

The project consists of the following main files:

- **index.html:** The main HTML file that contains the structure of the webpage.
- **app.js:** The JavaScript file that handles data fetching, processing, and chart generation.
- **samples.json:** The dataset that contains sample data of bacteria found in belly buttons.

## Technologies Used

- **D3.js:** For data manipulation and DOM interaction.
- **Plotly.js:** For building dynamic and interactive visualizations.
- **Bootstrap:** For basic styling and layout.
- **JavaScript (ES6):** Core functionality for fetching data, handling events, and creating visualizations.

## How It Works

1. **Initialization:**  
   The dashboard loads the sample data from `samples.json` and initializes the first test subject’s charts and metadata.
   
2. **Dynamic Charts:**  
   When a user selects a different test subject from the dropdown menu, the charts and demographic info are updated with the new data:
   - **Bar Chart:** Shows the top 10 OTUs (Operational Taxonomic Units) in the sample.
   - **Bubble Chart:** Provides a comprehensive view of all bacterial species found in the sample, with OTU ID on the x-axis and the frequency of bacteria on the y-axis.
   
3. **Metadata Display:**  
   The demographic information panel updates with the selected subject’s details, like age, gender, and location.

## Dataset

The dataset used in this project (`samples.json`) contains:
- **Metadata:** Information about each test subject, such as age, gender, and location.
- **Samples:** Bacterial species identified from the belly button of each test subject, with the frequency of each species.

## Acknowledgments

- The dataset and starter code provided by the course content on `https://static.bc-edx.com`.
