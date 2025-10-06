#Comparison Of Rainfall Between Seattle and Phan Thiet City

>This project aims to help visualize and analyze rainfall data for a specific timeframe (2018-2022) between two different cities. 
---

## Project Overview

This project was analyzed using the average precipitation data, and Python was used to create visualization graphs. The graphs were made using two different methods: one with mathlib and the other with seaborn. Both graph was produced similarly and consistently. The outcome revealed that each city experiences a different amount of precipitation throughout the year; Seattle appears to have higher precipitation than Phan Thiet. However, Phan Thiet data showed precipitation is trending toward the middle of the year more than in other months. This could be due to the Monsoon season. On the other hand, Seattle is more consistent throughout the year, with the highest levels around December and January. 

- **Objective: Compare and contrast the precipitation data between two cities
- **Domain:**: Science and Methodology
- **Key Techniques:** (e.g., Regression, Classification, Clustering, NLP, Time Series): Data loading and handling, grouping, data cleaning, data combining, data plotting.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** Link to the data source(s)
-  [Seattle rainfall dataset (seattle_rain.csv)]([https://github.com/YOUR_COURSE_REPO/weather_data](https://github.com/brian-fischer/DATA-5100/blob/main/weather/seattle_rain.csv))
-  [NOAA Climate Data Online Search](https://www.ncdc.noaa.gov/cdo-web/):  https://raw.githubusercontent.com/devlinhoang-cyber/Weather/refs/heads/main/Data/Phan%20Thiet%20station.csv
- **Description:** Brief overview of the dataset features, size, and format
- **License:** (if applicable)

---

## Analysis

Describe the notebooks and/or scripts used to perform the analysis. Specify the order in which the code should be run to reproduce the results.

The notebook began with data loading raw data via pandas.read_csv(). Then, verify and convert the date time column with pd.to_datetime(). Next, prepare the analysis by extracting data from the date column and grouping it. There is also a computational step for calculating the average precipitation from the data. After that, data clean-up was performed on the dataframe. Then, consolidate the data into a single dataframe. Lastly, visualize the analysis using a graph created with plt.bar() and sns.barplot. Either method demonstrated that data could be generated precisely and consistently. 
---

## Results

Include a short discussion of the findings and what they imply.

The results show that Seattle has more precipitation than Phan Thiet. Although Phan Thiet is located in a tropical climate, Seattle still receives higher total rainfall. This suggests that Seattle has more evenly distributed rainfall compared to Phan Thiet, where rainfall is concentrated at specific times of the year. Additionally, this proves that stations measure only rainfalls and not humidity. Measuring rainfall only would help reduce errors in interpreting the collected data. 
---

## Authors

-Dung (Devlin) Hoang - [@devlinhoang](https://github.com/devlinhoang)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
