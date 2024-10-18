# COVID-19 Data Analysis and Visualization

This project involves the analysis and visualization of COVID-19 data, providing insights into the global impact of the pandemic. The code is written in Python and utilizes various data analysis and visualization libraries. Below is a brief overview of the project components:

## Project Structure:
 
- **Notebook Files:**
  - `covid-19-marouane-haddad.ipynb`: The main Jupyter notebook containing the entire data analysis and visualization process.
  
- **Data File:**
  - `data.csv`: CSV file containing COVID-19 data. Make sure to replace it with the latest dataset if needed.

- **Libraries Used:** 
  - **pandas:** Data manipulation and analysis.
  - **matplotlib.pyplot:** Plotting and visualization.
  - **seaborn:** Statistical data visualization.
  - **numpy:** Mathematical operations.
  - **geopandas:** Used for geographical data plotting.

## Key Analysis Steps:

### 1. Data Loading and Cleaning:
   - Data is loaded from the 'data.csv' file.
   - Basic exploration, including data types, dimensions, and missing values, is performed.
   - A heatmap is generated to visualize missing data.

### 2. Visualization of COVID-19 Data in Morocco:
   - Bar charts, pie charts, and horizontal bar charts are used to visualize confirmed cases, deaths, and recoveries in Morocco.

### 3. Global Trends Visualization:
   - Top 10 countries are visualized with horizontal bar charts for confirmed cases, deaths, and recoveries.
   - Bar charts and pie charts show the distribution of confirmed cases by continent.

### 4. Evolution of Cases by Country or Continent:
   - Line charts display the evolution of confirmed cases, deaths, and recoveries in African and Eastern Mediterranean countries.

### 5. Global Heatmaps:
   - Three global heatmaps illustrate the worldwide distribution of confirmed cases, deaths, and recoveries.

### 6. Geographic Visualization: 
   - Geopandas is used to create maps showing the geographic distribution of confirmed cases, deaths, and recoveries.

## How to Use:

1. **Install Required Libraries:**
   - Make sure you have the required libraries installed. You can use the following command:
     ```
     pip install pandas matplotlib seaborn numpy geopandas
     ```

2. **Run the Jupyter Notebook:**
   - Open and run the `covid-19-marouane-haddad.ipynb` notebook using Jupyter or any compatible environment.

3. **Data Source:**
   - Ensure that the 'data.csv' file is up-to-date. You may replace it with the latest COVID-19 dataset.

4. **Explore and Customize:**
   - Feel free to explore different visualizations, customize parameters, or extend the analysis based on your requirements.

## Notes:
- Some visualizations may require additional libraries, such as geopandas, for mapping functionalities.
- Keep the data file updated for the latest COVID-19 information.

Feel free to contribute, provide feedback, or adapt the code for your own analysis. Stay safe!
