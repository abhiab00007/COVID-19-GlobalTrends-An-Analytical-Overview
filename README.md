# COVID-19 GlobalTrends-An Analytical Overview

Dataset chosen: https://www.kaggle.com/datasets/imdevskp/corona-virus-report
data tables from kaggle are imported to PowerBI and data is thoroughly preprocessed using DAX Expressions to ensure data quality.

## <u>Data Preprocessing Steps:</u>

1. Data Loading:Import and review
2. Data Cleaning:Eliminated irrelevant rows and columns that did not add value to the analysis (e.g., null headers or redundant metadata).
3. Handled Missing Values:Replaced missing values in critical columns with appropriate measures
3. Data Transformation:Corrected Data Types
4. Used DAX expressions to create New Measures:
   fatality rate, recovery rate and total confirmed cases from country wise latest table, 
   infection density per million people and testing efficiency from worldometer data table
5. Enhancing Data:Renamed Columns for Clarity,Adjusted column names for better readability
6. Added Conditional Formatting:Applied color scales to infection density rates for better visualization.
7. Created hierarchies (WHO Region → Continent → Country) for region-based analysis.
8. Managing relationships:Linked tables to establish relationships where required using the Manage Relationships pane, all relationships were set to the appropriate Cardinality
9. Validation and Finalization

## <u>Visualisations:</u>

visualisations are added to both content pages of the project  to convey insights effectively:
 
Page1:
1. Recovery Rate and Fatality Rate Cards:
to represent the percentage of recovered cases and fatalities out of total reported cases globally. They highlight the balance between recovery success and the pandemic's lethality.
2. Infection Density and Testing Efficiency Cards:
The infection density card shows the number of cases per million, indicating the spread relative to population size. The testing efficiency card measures the proportion of tests conducted relative to the population.
3. Percentage of Critical Cases Among Active Cases (Donut Chart):
This chart displays the proportion of critical cases compared to all active cases. 
4. Recovered vs. Deaths per 100 Cases (Donut Chart):
This visualization compares the ratio of recoveries to deaths for every 100 cases. It emphasizes recovery trends against fatalities.
5.Distribution of Total Cases per Million amoung WHO Regions, Continents and Countries (stacked column Chart):
The bar chart compares case densities across WHO regions, continents and countries using drillthrough option.It highlights areas with higher or lower infection burdens per million population.

Page 2:
1. Decomposition Tree – Critical Cases by WHO Regions:
This chart breaks down the critical case counts by WHO regions. It provides a clear view of the distribution of severe cases globally.
2. Total Recovered Cases by WHO Regions (Treemap):
The treemap visualizes the total recoveries across different regions. It helps identify where the most recoveries have been achieved.
3. Death Trend Throughout the Timeframe (Area Chart):
This area chart shows how the number of deaths increased over time globally. It reflects the timeline and impact of the pandemic's waves.
4. Count of Active Cases by Continent (Funnel Chart):
This chart represents the distribution of active cases across continents. It highlights which regions are currently most affected.
5. Infection Density Range Across Regions (Filled Map):
The map shows infection densities across the globe using color-coded ranges. It highlights regional hotspots and areas with fewer cases.

### <u>Slicer:</u>
WHO Region Filter :This slicer allows viewers to isolate data by WHO regions for a more detailed regional analysis. It helps compare metrics across Africa, Europe, the Americas, and other  WHO regions.

### <u>Interactive elements:</u>
Buttons, Bookmarks and Images are Incorporated to enhance user experience and to complement data analysis:
buttons are added on each pages to make effective navigavtion to pages that come before and after them.
A book mark is added to each page to smoothen slideshows.
Another bookmark is used for clearing the selections in the WHO Region slicer
Images related to the dataset topic are added to the aesthetics of the project


Neat Organization of Report is ensured by Clear titling, consistent colors, and thoughtful formatting to improve readability and aesthetics. 

## <u>Insightful Analysis derived from the data:</u>

##  Key Metrices

### 1. Recovery and Fatality Rates:

The 57% recovery rate highlights that over half of the global COVID-19 cases have recovered, showcasing progress in managing the pandemic.
A 3.97% fatality rate underlines the severity of the pandemic and the critical importance of healthcare interventions.

### 2. Testing Efficiency:

A 7.2% Testing Efficiency reflects efforts in scaling up testing globally, though region-specific disparities in testing rates might exist.

### 3. Infection Density:

An infection density of 3.03K per million indicates significant global spread, necessitating targeted containment and prevention strategies in highly dense areas.

### 4. Active vs. Critical Cases:

1% of active cases being critical highlights that most infections are manageable with standard care, while critical cases demand focused medical attention.

### 5. Recovered vs. Deaths:

For every 100 cases, 96 recover, while 4 result in fatalities, showing an encouraging recovery rate but also a need for continued vigilance and healthcare improvement.


##  Regional Dynamics and Trends

### 1. Critical Cases Distribution:

The decomposition tree shows the Americas leading with the highest number of critical cases, followed by South-East Asia and Europe, reflecting varying healthcare challenges.

### 2. Active Cases by Continent:

Asia, Europe, and North America have the largest shares of active cases, while Australia reports the lowest, possibly due to effective containment and lower population density.

### 3. Death Trends Over Time:

The death trend chart shows a steady increase from March to July 2020, emphasizing the urgency for mitigation measures during the peak.

### 4. Infection Density Map:

Regions with higher population densities exhibit larger infection densities, necessitating region-specific strategies for resource allocation and infection control.

### 5. Total Cases per Million:

Europe and the Americas display the highest case density, confirming them as global hotspots, while Africa and the Western Pacific show relatively lower densities.

### 6. Recoveries Across WHO Regions:

Recovery patterns highlight strong medical responses in certain regions, with Europe and the Americas leading recovery counts. However, lower recovery rates in some regions suggest gaps in healthcare capacity.
