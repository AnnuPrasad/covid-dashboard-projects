COVID-19 Data Visualization & Analysis 📊

📌 Overview
This project is a Python-based data analysis and visualization notebook that explores global COVID-19 data. It pulls real-time datasets from public repositories and generates interactive charts, maps, and widgets to better understand the spread and impact of the pandemic.
________________________________________
🚀 Features
•	📥 Fetches global COVID-19 datasets (confirmed, deaths, recovered)
•	📊 Data cleaning and preprocessing using Pandas
•	📈 Interactive visualizations using Plotly
•	🌍 Geospatial mapping using Folium
•	🎛️ Interactive widgets for country-level analysis
•	🎨 Styled tables for top affected countries
________________________________________
🛠️ Technologies Used
•	Python
•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn
•	Plotly (Express & Graph Objects)
•	Folium (for maps)
•	ipywidgets (for interactivity)
________________________________________
📂 Data Sources
Data is fetched from publicly available GitHub repositories:
•	Johns Hopkins University COVID-19 dataset
•	WHO dataset (commented in code)
________________________________________
⚙️ Installation
1.	Clone the repository:
git clone https://github.com/your-username/covid-analysis.git
cd covid-analysis
2.	Install required libraries:
pip install numpy pandas matplotlib seaborn plotly folium ipywidgets
3.	Run the notebook:
jupyter notebook

________________________________________
📊 Key Functionalities
1. Top 10 Affected Countries
•	Displays countries with the highest confirmed cases
•	Styled DataFrame highlighting key columns
2. Interactive Scatter Plot
•	Visualizes confirmed cases by country
•	Bubble size represents case count
3. Country-wise Trend Analysis
•	Interactive widget to select a country
•	Displays:
o	Confirmed cases over time
o	Death cases over time
4. Global COVID Map 🌍
•	Interactive Folium map
•	Circle markers represent case density
•	Tooltip shows:
o	Country name
o	Confirmed cases
o	Deaths
o	Death rate
________________________________________
🧠 How It Works
1.	Loads datasets from URLs
2.	Cleans and standardizes column names
3.	Aggregates data by country
4.	Generates:
o	Tables
o	Charts
o	Interactive widgets
o	Maps
________________________________________
⚠️ Notes
•	The notebook uses live data sources, so results may change over time
•	Ensure Jupyter Notebook is trusted to display maps:
•	File → Trust Notebook
•	You may see a deprecation warning:
•	Importing display from IPython.core.display is deprecated
✔ Fix:
from IPython.display import display, HTML
________________________________________
📸 Sample Outputs
•	Scatter plots of global cases
•	Time-series trends per country
•	Interactive world map with COVID stats
________________________________________
👨‍💻 Author
Annu Prasad


