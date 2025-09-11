
# DataFun-04-EDA: Exploratory Data Analysis of the Iris Dataset

This project demonstrates a complete exploratory data analysis (EDA) workflow using the classic Iris dataset. The goal is to show how Python tools can be used to load, inspect, visualize, and engineer features from data, and to draw meaningful insights about the relationships between variables and species.

## Project Overview
- **Dataset:** Iris flower dataset (150 samples, 4 features, 3 species)
- **Tools Used:** Python, pandas, seaborn, matplotlib
- **Notebook:** All analysis is documented in `TestDrive.ipynb`.

## Key Steps Performed
1. **Data Loading:** Imported the Iris dataset using seaborn and loaded it into a pandas DataFrame.
2. **Data Inspection:** Explored the structure, types, and summary statistics of the data.
3. **Visualization:** Created histograms, pairplots, and scatter plots to visualize distributions and relationships.
4. **Feature Engineering:** Created a new feature (Sepal Area) to explore additional relationships.
5. **Analysis:** Compared species using visualizations and statistics to identify which features best separate them.
6. **Insights:** Summarized findings and highlighted the most predictive features for species classification.

## Results
- Petal measurements (length and width) are the most effective for distinguishing species, especially Setosa.
- Sepal measurements and engineered features like Sepal Area provide additional, but less powerful, separation.
- Visualizations clearly show patterns and support the conclusions drawn from the data.

## How to Use This Project
1. Clone the repository:
	```bash
	git clone https://github.com/KHenn22/datafun-04-eda.git
	cd datafun-04-eda
	```
2. Create and activate a virtual environment:
	```bash
	python3 -m venv .venv
	source .venv/bin/activate
	```
3. Install dependencies:
	```bash
	pip install -r requirements.txt
	```
4. Open `TestDrive.ipynb` in Jupyter or VS Code and run the cells to reproduce the analysis.

## Requirements
- Python 3.8 or higher
- See `requirements.txt` for package list

## Project Status
**Complete as of 9/10/2025.**

## Status 9/10/2025
Project complete. The exploratory analysis in `TestDrive.ipynb` was finalized on 9/10/2025.

### Prerequisites
- Python 3.8+
- Recommended: Use a virtual environment

### Setup
1. Clone the repository:
	```bash
	git clone https://github.com/KHenn22/datafun-04-eda.git
	cd datafun-04-eda
	```
2. Create and activate a virtual environment:
	```bash
	python3 -m venv .venv
	source .venv/bin/activate
	```
3. Install dependencies:
	```bash
	pip install -r requirements.txt
	```
