# Generic Real Estate Consulting Project
- Group number: 16


**Research Goal:**  Our research goal is rental property analysis in Victoria, Australia 

**Timeline:** The timeline for the research area is 2024-09-01 - 2024-10-17.

**Directory Structure**

1. see the `scrape.py` file in the `scripts` directory to get started scraping data. 

2. notebooks
    2.1 `preprocessing_rent`:  contains notebooks for preprocessing rent-related data.
    2.2 `preprocessing_external`: contains notebooks for external data preprocessing including schools, parks,          transportations, population and income data.
    2.3 `Analysis`: contains notebooks related to specific analytical tasks. `growth_rate.ipynb` and `Most_liveable.ipynb` answerd two of the problems and `Visual_operation.ipynb` conduct analysis on the curated data. The rest of notebooks focused on distance-related analysis.

3. models: These notebooks are used to fit the models and analyze them.
    - `Linear_regression.ipynb`: This notebook implements a linear regression model
    - `model-XGBoost.ipynb`: This notebook implements an XGBoost model
    - `test.ipynb`: This notebook created a test dataset with all features in training data and an empty rental prices column.

**Essential code**
1. models: including models, evaluation and plots
2. Analysis: contains notebooks related to specific analytical tasks

Note: there are many assumptions made in external and internal dataset.

**External Data Resources**

Victoria State Government. "Parks and Conservation Reserves (PARKRES)." Data.Vic. https://discover.data.vic.gov.au/dataset/parks-and-conservation-reserves-parkres. Victoria State Government. "School Locations 2023." Data.Vic. https://discover.data.vic.gov.au/dataset/school-locations-2023.
Victoria State Government. "Victoria School Locations 2018." AURIN Data Provider Access. https://adp-access.aurin.org.au/dataset/vic-govt-det-vic-school-locations-2018-na. Victoria State Government. "Postcodes." Data.Vic. https://discover.data.vic.gov.au/dataset/postcodes.
Victoria State Government. "PTV Regional Train Stations." Data.Vic. https://discover.data.vic.gov.au/dataset/ptv-regional-train-stations. Victoria State Government. "PTV Metro Tram Stops." Data.Vic. https://discover.data.vic.gov.au/dataset/ptv-metro-tram-stops.
Victoria State Government. "PTV Regional Bus Routes." Data.Vic. https://discover.data.vic.gov.au/dataset/ptv-regional-bus-routes. Proctor, Matthew. "Australian Postcodes." GitHub. https://github.com/matthewproctor/australianpostcodes/tree/master.
Australian Bureau of Statistics. "Regional Population by Age and Sex." ABS. https://www.abs.gov.au/statistics/people/population/regional-population-age-and-sex/latest-release#data-downloads. Australian Bureau of Statistics. "Personal Income in Australia." ABS. https://www.abs.gov.au/statistics/labour/earnings-and-working-conditions/personal-income-australia.
Australian Bureau of Statistics. "Australian Statistical Geography Standard (ASGS), Edition 3: Correspondences." ABS. https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/correspondences.



