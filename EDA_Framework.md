# EDA Framework: Analysis Dimensions, Charts, and Purpose

## 1. Data Quality Check

### What we can analyse
- Missing values
- Duplicate records
- Whether timestamp fields can be correctly converted
- Whether occupancy values contain negative values, zeros, or extreme values
- Whether `locationcode` can be matched with room and building metadata

### Possible charts / methods
- Missing value table
- Duplicate count summary
- Descriptive statistics table
- Top abnormal values table

### Purpose
This helps us understand whether the dataset is ready for further analysis and identify potential issues that need to be confirmed with KIT or the supervisor, such as negative values, extreme values, or unmatched room codes.


## 2. Occupancy Value Distribution

### What we can analyse
- Overall distribution of occupancy values
- The common range of occupancy values
- Whether there are clear outliers
- Whether there are many zero values

### Possible charts
- Histogram
- Boxplot
- Top 10 largest occupancy values table

### Purpose
This helps us understand the basic characteristics of the occupancy data and detect possible abnormal values that may require further checking.


## 3. Temporal Analysis

### What we can analyse
- Average occupancy by hour
- Differences between morning, afternoon, and evening usage
- Differences between weekdays and weekends
- Daily occupancy trends
- Whether there are unusual peaks or drops on specific dates

### Possible charts
- Line chart: average occupancy by hour
- Bar chart: average occupancy by weekday
- Line chart: daily average occupancy trend
- Boxplot: occupancy by weekday / weekend

### Purpose
This helps us identify time-based usage patterns, such as peak usage periods, low-usage periods, and differences between weekdays and weekends.


## 4. Location / Room-Level Analysis

### What we can analyse
- Which locations have the highest average occupancy
- Which locations are frequently empty
- Whether usage differs across rooms
- Which rooms have more or fewer observation records

### Possible charts
- Bar chart: top 10 rooms by average occupancy
- Bar chart: top 10 rooms by maximum occupancy
- Bar chart: number of records by location
- Summary table by `locationcode`

### Purpose
This helps us identify specific rooms with high or low usage and understand whether the data coverage is balanced across locations.


## 5. Room Capacity / Occupancy Rate Analysis

### What we can analyse
- Relationship between observed occupancy and room capacity
- Occupancy rate, calculated as:  
  `occupancy rate = occupancy value / room capacity`
- Which rooms are close to full capacity
- Which large rooms have low utilisation
- Whether any occupancy values are greater than room capacity

### Possible charts
- Histogram: occupancy rate distribution
- Boxplot: occupancy rate distribution
- Bar chart: top 10 rooms by average occupancy rate
- Scatter plot: room capacity vs average occupancy
- Table: rooms with occupancy rate above 100%

### Purpose
Occupancy rate allows us to compare rooms of different sizes more fairly. This is one of the most important indicators for understanding space utilisation.


## 6. Room Type / Room Category Analysis

### What we can analyse
- Average occupancy by room type
- Average occupancy rate by room category
- Differences between lecture rooms, labs, tutorial rooms, and other spaces
- Which types of rooms are more heavily used or underused

### Possible charts
- Bar chart: average occupancy by room type
- Bar chart: average occupancy rate by room category
- Boxplot: occupancy rate by room type
- Summary table by room type / category

### Purpose
This helps us compare how different types of teaching or learning spaces are used and identify which room categories have higher or lower utilisation.


## 7. Room Size / Area Analysis

### What we can analyse
- Whether room area and room capacity are consistent
- Whether larger rooms have higher occupancy
- Occupancy density, calculated as:  
  `occupancy density = occupancy value / room area`
- Differences in usage intensity across room types

### Possible charts
- Scatter plot: room area vs room capacity
- Scatter plot: room area vs average occupancy
- Histogram: occupancy density
- Boxplot: occupancy density by room type

### Purpose
This helps us understand how intensively physical space is used and whether larger rooms are actually being used more efficiently.


## 8. Building-Level Analysis

### What we can analyse
- Which buildings have the highest average occupancy
- Which buildings have the highest total usage
- Whether occupancy rates differ across buildings
- Which buildings may be underutilised

### Possible charts
- Bar chart: top 10 buildings by average occupancy
- Bar chart: top 10 buildings by average occupancy rate
- Summary table by building name
- Boxplot: occupancy rate by building

### Purpose
This provides a higher-level view of space usage across buildings and is useful for presenting overall campus space utilisation patterns.


## 9. Campus-Level Analysis

### What we can analyse
- Average occupancy by campus
- Average occupancy rate by campus
- Whether space usage is concentrated in specific campuses
- Whether campuses have different usage patterns

### Possible charts
- Bar chart: average occupancy by campus
- Bar chart: average occupancy rate by campus
- Boxplot: occupancy rate by campus

### Purpose
This allows us to compare space usage at a broader campus level and understand whether utilisation differs across campuses.


## 10. Spatial / Map-Based Analysis

### What we can analyse
- Where high-occupancy buildings are located
- Which areas have more intensive space usage
- Whether spatial location is related to occupancy patterns

### Possible charts
- Map visualisation using longitude and latitude
- Spatial scatter plot
- Bubble map: bubble size represents average occupancy or occupancy rate

### Purpose
This makes the results more intuitive by showing occupancy patterns on a campus map, which can be useful for presentations to non-technical audiences.


## 11. Outlier and Follow-Up Issue Analysis

### What we can analyse
- Records with `value < 0`
- Records with `value = 0`
- Records where `value > room capacity`
- `locationcode` values that cannot be matched with room metadata
- Rooms with missing capacity or building information

### Possible charts / methods
- Abnormal records table
- Count summary table
- Bar chart: number of abnormal records by building / room type

### Purpose
This helps us summarise key data issues and prepare follow-up questions for KIT or the supervisor.
