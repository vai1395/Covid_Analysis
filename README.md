# COVID-19 Analysis Project

## Project Selection

### Project Narrative

Our group embarked on a project to visualize the global spread and treatment of COVID-19 from 2020 to 2023, leveraging the power of [Tableau](https://github.com/vai1395/Covid_Analysis/blob/main/Covid_Analysis_Dashboard.twbx) for impactful data visualization. The choice was influenced by the global significance of the pandemic and the opportunity to apply data management skills in a real-world context. We aimed to provide deep insights into the pandemic's spread, identify hotspots, and analyze the measures taken during this period.

## Data Acquisition

### Dataset

We obtained COVID-19 statistics from "Our World in Data," encompassing comprehensive information such as total cases, deaths, and vaccination details. However, the data acquisition process faced challenges, including connection errors, JSON file size limitations, and licensing complications with MongoDB Atlas.

### Data Challenges

- Connection errors during data retrieval
- JSON file size limitations (16 MB) posing restrictions
- Licensing complications with MongoDB Atlas
- Creating seamless dashboards in Tableau

Despite these challenges, Python was used for data cleaning, and the refined data was successfully loaded into MongoDB for further visualization.

### Data Sampling

The raw data comprised over 350,000 rows and 67 columns, providing a comprehensive view of the pandemic from 2020 to 2023.

## Data Cleaning (ETL)

We employed [Python](https://github.com/vai1395/Covid_Analysis/blob/main/IM%20Project%20-%20Data%20Cleaning.ipynb) for data cleaning, focusing on removing null values, fixing data granularity, and improving overall data quality. The cleaned data was stored in MongoDB for quick extraction and visualization in Tableau.

### Cleaning Steps

- Handling nulls and missing values
- Improving data granularity for specific columns like Location, Income, and continents

## Research Questions

Our project aimed to answer key questions:

- How has the COVID-19 scenario evolved historically?
- What insights can be derived by filtering data by continent, country, date, and age group?
- How can these insights contribute to informed decision-making?

## Tools and Technology

We utilized a combination of tools:

- **Python**: Used for data exploration and cleaning.
- **MongoDB**: Served as the database for storing cleaned data.
- **Tableau**: Utilized for creating visually impactful dashboards and extracting meaningful insights.

## Real-Life Impact

The outcomes of our work have real-life implications:

- **Historical Perspective**: Understanding the historical evolution of the COVID-19 pandemic.
- **Granular Insights**: Deriving detailed insights by focusing on specific data points.
- **Informed Decision-Making**: Contributing to more informed public health strategies and emergency responses. The project aids in addressing the dynamic nature of COVID-19.
