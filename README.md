# EV-Market-Size-Analysis
Market size analysis is a crucial aspect of market research that determines the potential sales volume within a given market. It helps businesses understand the magnitude of demand, assess market saturation levels, and identify growth opportunities.
## Project Overview : 
The Electric Vehicles Market Size Analysis project will involve collecting, cleaning, and analyzing data to understand the current and projected market size of electric vehicles. The analysis will cover global, regional, and country-specific markets, identifying key trends, growth drivers, and strategic opportunities. The final deliverables will include a detailed report with actionable recommendations and a series of visualizations to communicate findings effectively.

## Tools and Technologies : 
- Python: For data analysis and visualization.
- Pandas and NumPy: For data manipulation and analysis.
- Matplotlib, Seaborn, and Plotly: For creating visualizations.
-  Jupyter Notebooks: For interactive data analysis and reporting.

## Dataset Description : 
We will use this dataset for the analysis:  Electric_Vehicle_Population_Data.csv

### EV Population Data: 
- Dataset Name: Electric Vehicle Population Data
- Source: User-uploaded dataset containing detailed information about electric vehicles, including their make, model, year, type, electric range, and location.
- Citation: This dataset is provided by the user and includes data on various attributes of electric vehicles, such as VIN, county, city, state, postal code, model year, make, model, electric vehicle type, clean alternative fuel vehicle eligibility, electric range, base MSRP, legislative district, DOL vehicle ID, vehicle location, electric utility, and 2020 census tract.

### Problem statements : 
1. Define whether the analysis is global, regional, or focused on specific countries.
2. Gather information from industry associations, market research firms (e.g., BloombergNEF, IEA), and government publications relevant to the EV market.
3. Use historical data to identify trends in EV sales, production, and market.
4. Analyze the market size and growth rates for different EV segments.
5. Based on the market size analysis, provide strategic recommendations for businesses looking to enter or expand in the EV market.

## Step-by-Step Analysis
•	Importing Necessary Libraries and Loading Data - Begin by importing essential libraries such as pandas, matplotlib, seaborn, numpy, and the curve fit function from scipy.optimize. Load the dataset to start the analysis.

```shell
pip install numpy
```
```shell
pip install pandas
```
```shell
pip install matplotlib
```
```shell
pip install seaborn
```
```shell
import pandas as pd
ev_data = pd.read_csv('Electric_Vehicle_Population_Data.csv')
print(ev_data.head())
```
![1](https://github.com/aniket3096/Electric_Vehicles_Market/assets/164318183/fe3dd857-7ba5-4c86-929d-11e8613bccf6)

•	Data Cleaning - Ensure the dataset is clean by handling missing values and verifying appropriate data types. This step is crucial for accurate analysis.
```shell
ev_data.info()
```

![2](https://github.com/aniket3096/Electric_Vehicles_Market/assets/164318183/ec5b5d05-34c9-4f38-856e-2f71b6ecdeb0)

```shell
ev_data.isnull().sum()
```

```shell
ev_data = ev_data.dropna()
```

 ## For the task of market size of electric vehicles analysis, we can explore the following areas:

- EV Adoption Over Time: Analyze the growth of the EV population by model year.
- Geographical Distribution: Understand where EVs are most commonly registered (e.g., by county or city).
- EV Types: Breakdown of the dataset by electric vehicle type (BEV, etc.).
- Make and Model Popularity: Identify the most popular makes and models among the registered EVs.
- Electric Range Analysis: Analyze the electric range of vehicles to see how EV technology is progressing.
- Estimated Growth in Market Size: Analyze and find the estimated growth in the market size of electric vehicles.

