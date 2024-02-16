# belly-button-challenge
This repository contains an interactive web visualization dashboard that analyzes sample data obtained from belly button microbial studies. The dashboard consists of two main visualizations: a horizontal bar chart and a bubble chart, along with sample metadata display.

## OBJECTIVE 
The objective of this project is to create an interactive dashboard that allows users to explore sample data collected from individuals' belly buttons. The dashboard provides insights into the top 10 Operational Taxonomic Units (OTUs) found in each individual, along with their demographic information.

## DATA ACQUISITION:
samples.json

## VISUALS 
Horizontal Bar Chart: Displays the top 10 OTUs found in the selected individual, with sample values as the bar lengths, and OTU IDs as labels.
Bubble Chart: Visualizes each sample with OTU IDs as x-values, sample values as y-values, sample values as marker sizes, OTU IDs as marker colors, and OTU labels as text values.
Sample Metadata Display: Shows the demographic information of the selected individual, displaying each key-value pair from the metadata JSON object.


## REPOSITORY STRUCTURE
index.html: Main HTML file containing the structure of the dashboard.
static: Directory containing JavaScript and CSS files.
js: JavaScript files for data loading and visualization.
app.js: Main JavaScript file for initializing visualizations and handling user interactions.
css: CSS files for styling the dashboard.
style.css: Custom styles for the dashboard.
samples.json: Data file containing sample information.
