# Wikipedia Data Analysis

## Project Overview

This project explores Wikipedia language editions from two perspectives:

1. **Quality vs Quantity Analysis**  
   We analyze how each Wikipedia edition differs in content quantity (number of articles) and content quality (Depth score). The dataset is divided into four groups:  
   - High Quantity – High Quality  
   - High Quantity – Low Quality  
   - Low Quantity – High Quality  
   - Low Quantity – Low Quality  

## Data Source

The dataset `wikipedias.csv` was collected through web scraping from publicly available Wikipedia statistical resources.  
It contains metrics for 300+ language editions, including articles, edits, admin count, user count, and Depth.

## Repository Structure

- **`Eda_on_wikipedias.ipynb`**  
  Contains all steps: data scraping, cleaning, EDA, Quality vs Quantity classification, visualizations, and predictive modeling.

- **`wikipedias.csv`**  
  The raw dataset.

- **`results/` folder**  
  Contains all exported visualizations such as:
  - Histograms (Articles, Depth)
  - Scatter plots (Articles vs Depth)
  - Quadrant plots (Quality vs Quantity)
  - Correlation heatmaps

- **`.gitignore`**  
  Used to exclude temporary files (e.g., `.ipynb_checkpoints/`).


## Saved Visualizations to the Results Folder

