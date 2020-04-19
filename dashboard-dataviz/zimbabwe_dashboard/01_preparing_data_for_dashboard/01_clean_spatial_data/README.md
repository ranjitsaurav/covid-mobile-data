# Clean Spatial Data

Cleans spatial datasets:
1. Aggregate units when needed (e.g., aggregating wards)
2. Add additional variables (e.g., area)
3. Standardize variable names
4. Orders spatial data by region

### Standardize Variable Names
Each spatial dataset should have standardized variable names. Standardizing
variable names helps ensure different units (eg, admin2, admin3) can be
easily switched in the dashboard
* __name:__ Name of the unit
* __region:__ Unique unit identifier id
* __area:__ Are of the unit in kilometers squared
* __province:__ Name of the province that the unit is in

### Order Spatial Data
Spatial datasets are ordered by region. When cleaning other datasets at the
region level, we also order by region and ensure all regions are present. This
ensures that no reordering needs to be done in the dashboard.