# COVID-19 Global Data Tracker


## Project Description
This project analyzes global COVID-19 trends using data from Our World in Data. It provides interactive visualizations of cases, deaths, and vaccination progress across countries and time periods. The analysis is available both as a Jupyter Notebook report and an interactive Streamlit dashboard.

## Project Objectives
- Import and clean COVID-19 global data
- Analyze time trends (cases, deaths, vaccinations)
- Compare metrics across countries/regions
- Visualize trends with interactive charts
- Create an interactive dashboard with user controls

## Tools and Libraries Used
- Python 3.8+
- Jupyter Notebook
- pandas (data manipulation)
- NumPy (numerical operations)
- Matplotlib (static visualizations)
- Seaborn (statistical visualizations)
- Plotly Express (interactive visualizations)
- Streamlit (dashboard interface)

## How to Use

### Option 1: Jupyter Notebook Analysis
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Run Jupyter Notebook: `jupyter notebook`
4. Open `COVID_19_Analysis.ipynb`

### Option 2: Streamlit Dashboard
1. Install Streamlit: `pip install streamlit`
2. Run the dashboard: `streamlit run dashboard.py`
3. Use sidebar controls to select countries and date ranges

### Dataset
The project uses `owid-covid-data.csv` from [Our World in Data](https://ourworldindata.org/covid-deaths). A cleaned version is included as `cleaned_covid_data.csv`.

## Key Insights
1. **Global Patterns**: The data shows distinct waves of infection corresponding to new variants
2. **Vaccination Impact**: Countries with faster vaccine rollouts saw reduced mortality in later waves
3. **Regional Differences**: Case fatality rates varied significantly by region, likely reflecting healthcare system differences
4. **Temporal Trends**: Most countries experienced multiple infection peaks before reaching endemic stages

## Reflections
This project demonstrated:
- The importance of data cleaning for real-world datasets
- How interactive visualizations can reveal patterns in complex data
- The value of comparative analysis across countries
- Challenges in normalizing health metrics across different populations

## Future Enhancements
- Add hospitalization/ICU data
- Incorporate mobility data correlations
- Build country comparison tool
- Add vaccination brand distribution
