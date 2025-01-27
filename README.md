<h1>Wildfire Data Visualization with Folium</h1>
<h2>Overview</h2>
Analyzing and visualizing wildfire occurrences in the United States using geospatial data. The dataset is processed using Python libraries and displayed interactively on a Folium map.

<h2>Features</h2>

- Cleans and processes wildfire geospatial data from a CSV file.
- Filters fires based on size and location.
- Creates an interactive map displaying large wildfire events (over 10,000 acres) with relevant details.
  
<h2>Installation</h2>

- Clone this repository and navigate to the project folder.
- Install the required Python libraries:
  
```bash
pip install pandas numpy matplotlib nltk transformers
```

<h2>Dataset</h2>
The project uses a CSV file: National_USFS_Fire_Occurrence_Point_(Feature_Layer).csv, which includes geospatial wildfire data such as:

- Coordinates (Longitude: LONGDD83, Latitude: LATDD83)
- Fire Name (FIRENAME)
- Fire Year (FIREYEAR)
- Burned Area (TOTALACRES)
Ensure the dataset is placed in the project folder.
