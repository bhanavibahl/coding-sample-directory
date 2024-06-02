## Project Name: "Causal Inference Analysis of the Impact of Improved Drinking Water Sources on Mortality Rates Attributed to Unsafe Water in Selected Countries 2001-2019" 
## Author: Bhanavi Bahl
## Date: 02/06/2023

Project Overview and Aims: This project attempts to draw a correlation between water sanitation and water-borne disease-related mortality rates. The inferences are drawn from a study conducted by the World Health Organisation. The report suggests that there's an estimate of over 1 million deaths resulting from diarrhoea alone; an illness caused by the consumption of unsafe drinking water. 

## Data Sources: 
United Nations SDG Water Data: Provides data on the proportion of the population using improved drinking water sources.
2. Our World In Data: Provides data on the share of deaths attributed to unsafe water sources.

## Files Included
- `safe_water_source`: Contains the manually created data for the proportion of the population using improved drinking water sources for the selected countries.
- `water_deaths`: Contains data on the share of deaths attributed to unsafe water sources for the selected countries.
- 'Rplot-water.pdf': Contains the multiple linear regression scatter plot. 

## Instructions to Run the Analysis
1. **Clone the Repository**:
    ```sh
    (https://github.com/bhanavibahl/coding-sample-directory.git)    ```

2. **Install Required Libraries**:
    Make sure you have R installed. Then, install the required libraries using the following commands in R:
    ```r
    install.packages(c("tidyverse", "ggplot2", "dplyr", "readr"))
    ```

3. **Load the Data**:
    Ensure that `water_deaths.csv` and `safe_water_source` are in the same directory, then load the data. 

4. **Run the Analysis**:
    Use 'merged_data' (the data set that has data from 'water_data.csv' and 'safe_water_source'. 

## Key Steps in the Analysis
1. **Loading Required Libraries**: `tidyverse`, `ggplot2`, `dplyr`, `readr`
2. **Creating Data Frames**: Manually creating `safe_water_source` based on provided data.
3. **Filtering and Merging Data**: Filtering `water_data` for the selected countries and years, and merging it with `safe_water_source`.
4. **Calculating R-squared Value**: Calculating a single overall R-squared value for the combined dataset to understand the strength of the relationship.
5. **Plotting**: Creating a scatter plot with linear regression lines for each country.

## Key Results
- The overall R-squared value indicates the strength of the relationship between improved water sources and reduced mortality rates due to unsafe water.
- Visualization of this relationship for each country provides insights into the varying impacts across different regions.

## Conclusion
The analysis provides evidence of the importance of access to safe drinking water in reducing mortality rates attributed to unsafe water sources. It highlights significant disparities between countries and underscores the need for targeted interventions.

## Acknowledgments
- United Nations SDG Water Data
- Our World In Data

## License
This project is licensed under the Creative Commons Legal Code- see the LICENSE.md file for details.

## Contact
For any questions or comments, please contact Bhanavi Bahl at [bahlbhanavi@gmail.com].
