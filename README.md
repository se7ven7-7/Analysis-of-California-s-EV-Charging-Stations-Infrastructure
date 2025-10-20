## Executive Summary  

California aims to achieve a fully zero-emission transportation system by 2035. As electric vehicle (EV) adoption accelerates, the state faces growing pressure to expand its charging infrastructure equitably and efficiently. This project evaluates California’s readiness to meet future EV charging demand by analyzing spatial disparities between EV registrations, population density, and charger distribution.  

The analysis reveals regions where EV infrastructure remains underdeveloped and at risk of overloading due to rapid EV adoption. It also identifies potential business opportunities for private and public investment in underserved areas. The findings suggest that targeted funding allocation can help balance regional disparities and ensure California’s successful transition toward an emission-free transportation future.  

---

## Project Description  

This project investigates geographic and economic imbalances in California’s EV charging network. By comparing the distribution of charging stations with EV registration data and population density, it identifies areas where infrastructure development lags behind EV growth. The project also incorporates EV sales forecasts to anticipate future charging demand and guide data-driven decision-making for policymakers and investors.  

---

## Data Sources and Methodology  

The project integrates multiple open data sources to analyze EV infrastructure and demographic patterns across California:  

- **California ZIP Code Population Data** — [California Demographics](https://www.california-demographics.com/zip_codes_by_population)  
  Provides ZIP code–level population estimates used for demographic normalization and density-based analysis.  

- **Vehicle Fuel Type Count by ZIP Code** — [Data.gov](https://catalog.data.gov/dataset/vehicle-fuel-type-count-by-zip-code)  
  Contains information on the number of registered vehicles by fuel type (gasoline, hybrid, electric) across California ZIP codes.  

- **Alternative Fueling Stations Dataset** — [U.S. Department of Transportation](https://data-usdot.opendata.arcgis.com/datasets/alternative-fueling-stations/explore)  
  Includes geospatial data for public and private EV charging stations, used to map charger availability and network density.  

- **U.S. ZIP Code Geolocation Database** — [United States ZIP Codes](https://www.unitedstateszipcodes.org/zip-code-database/)  
  Provides ZIP code boundaries and coordinates for spatial mapping and regional aggregation.  

- **California Administrative Boundaries** — [California Geoportal](https://gis.data.ca.gov/datasets/dea966d601934f49b9a0e1668182801b_0/explore?location=36.773198%2C-119.005050%2C6.02&showTable=true)  
  Offers shapefiles for county and regional boundaries used in geographic visualization and analysis.  

### Methodology Overview  
- **Data Cleaning & Integration:** Conducted in *Python (pandas, NumPy)* to standardize and merge datasets from multiple public sources.  
- **Geospatial Analysis:** Performed using *GeoPandas* and *Shapely* to visualize charger density and regional disparities.  
- **Forecasting & Modeling:** Future EV demand projected using *regression modeling* based on historical adoption trends.  
- **Visualization:** Interactive maps and dashboards built in *Tableau* and *Matplotlib* to highlight infrastructure gaps and policy insights.  

---

## Introduction and Motivation  

California currently has over 150,000 public and private chargers installed statewide and continues to lead the nation in zero-emission transportation initiatives. The state is projected to receive over **$380 million** from the **Infrastructure Investment and Jobs Act (IIJA)** and more than **$1 billion** in total for EV and hydrogen refueling infrastructure.  

Despite this progress, the surge in EV ownership presents new challenges for infrastructure readiness, particularly in regions with limited charger density. As the EV supply equipment (EVSE) industry is projected to reach **$100 billion in U.S. market value by 2040**, ensuring an equitable and efficient distribution of charging resources is critical.  

The motivation for this project is to:  
- Evaluate the adequacy of California’s existing EV infrastructure.  
- Identify spatial and investment gaps in charger accessibility.  
- Forecast future EV and charging demand to assess statewide readiness.  

By integrating demographic, spatial, and infrastructure data, this analysis provides insights into California’s ability to meet its 2035 zero-emission goals while identifying regions with high potential for infrastructure growth.  
