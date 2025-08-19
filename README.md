# povGeoData
Welcome to the curated respository of spatial data and methods relevant to the work of World Bank poverty economists.

**Data** sources and indicators are listed by theme with important attributes, simple instructions to access each data source and existing applications.

**Methods** to perform basic analysis tasks are listed by type with reproducible examples. 

## Data sources
We focus on spatial indicators and data sources that are useful for welfare analysis, easy to construct or access and are well documented. 
All indicators in the list follow a standard to help users find and compare options. Each item has the following attributes:

- `theme`: Broad category of variable
- `name`: Variable name
- `source`: Data source
- `description`: Precise description of the variable
- `units`: Units of measurement for the variable
- `spatial coverage`: Spatial coverage of source data (what countries?)
- `spatial resolution`: Spatial resolution of the source data (e.g., 5km, 30", 0.5°...)
- `temporal coverage`: Temporal coverage/extent of the source data (what range of years are available?)
- `temporal resolution`: Temporal resolution of the source data (e.g., daily, monthly, annual...)
- `reference`: Link to the data source reference/paper/doi (e.g., "https://doi.org/10.1080/17538947.2024.2390454")
- `examples`: Link to relevant applications using the data (optional)

### GMD Spatial
The World Bank's Global Monitoring Database (GMD) now includes harmonized variables describing the location and spatial context of interviewed households. 
Locations in surveys were mapped to a discrete global grid system (H3 hexagons). 
This is used as a key to merge geospatial data from other sources.

- The LOC module describes the type of location information available from the household survey.
- The H3 module maps interview locations to the global grid system.
- The SPAT module provides location and time matched spatial variables.

The survey merged geo-variables currently available from GMD are listed [here](). 
In addition to the attributes above, this describes how the source data was aggregated to the spatial units in the survey. 
More spatial variables will be added over time. 

Reproducible examples to access and analyse the GMD data using Stata or R can be found on [this page]().

## Methods
We describe common steps to process or analyse spatial data. 
The initial focus is on generic tasks that can be adapted for specific use cases and inputs.
All methods are described using the following schema for ease of use and discovery:

- `type`: Type of method (e.g. Aggregation)
- `name`: Name of method (e.g. Zonal statistics)
- `description`: "Description of what the method does"
- `input`: "What inputs are required?"
- `output`: "What is the output?"
- `reprex`: "Reproducible code, with sample data (R and/or Stata)"
- `question`: "What is a (policy) question this method/example could answer?"

## Do you want to contribute?
The easiest way to contribute to the list or make a request is to [open an issue on Github](https://github.com/wbpovgeo/povGeoData/issues).
You will be able to choose the relevant template: `contribute data`, `contribute method`, `request data`, `request method`.
Filling out the template ensures you provide all the information we need. We will use the information to check the data source, test the method, or create a new entry for your request.

## Do you want to learn?
Link to resources, training materials

## Do you need hands-on support?
How to request it... How to find consultants
