# Wikipedia Quality Prediction: Modeling Editorial Depth

## Project Overview
This project focuses on **predicting the 'Depth'** of various Wikipedia language editions, a metric used to quantify the quality and collaborative health of a wiki. We aim to identify which factors—such as the number of active users, total edits, and administrative support—are the most significant drivers of a high-quality, well-maintained platform.

## Data Source
The raw data, `wikipedias.csv`, was collected via **web scraping** from a public list of Wikipedia statistics. It contains key metrics for over 300 language editions.

## Repository Structure
- `[Your_Notebook_Name].ipynb`: Contains all code for data collection, cleaning, Exploratory Data Analysis (EDA), and predictive modeling.
- `wikipedias.csv`: The raw dataset used for the analysis.
- `.gitignore`: Specifies files to be excluded from version control (e.g., temporary checkpoint files).

## Target Variable
- **Depth (Target)**: A Wikipedia metric calculated using the ratio of edits and non-article pages (talk pages, project pages) to the total number of articles. High depth indicates a strong, collaborative community.