# Weather-Data-Analysis

# Weather Data Analysis

This project involves performing data analysis on weather data using Python and the pandas library.

## Dataset

The dataset used is `Project+1+-+Weather+Dataset.csv`. It contains various weather-related information, including date/time, temperature, dew point temperature, relative humidity, wind speed, visibility, pressure, and weather conditions.

## Project Goals

The primary goals of this project are to analyze the weather dataset using pandas. Specific operations include:

1.  Finding all unique values in the 'Wind Speed' column.
   
2.  Determining the number of times the 'Weather' is exactly 'Clear'.
   
3.  Finding the number of times 'Wind Speed' was exactly 4 km/h.
   
4.  Identifying null values in the data.
   
5.  Renaming the 'Weather' column to 'Weather Condition'.
   
6.  Calculating the mean 'Visibility'.
   
7.  Calculating the standard deviation of 'Pressure'.
   
8.  Calculating the variance of 'Relative Humidity'.
   
9.  Finding all instances when 'Snow' was recorded.
   
10. Finding all instances when 'Wind Speed' is above 24 and 'Visibility' is 25.
   
11. Determining the mean value of each column against each 'Weather Condition'.
   
12. Finding all instances when:
    * 'Weather Condition' is 'Clear' and 'Relative Humidity' is greater than 50.
    * 'Visibility' is above 40.

## Libraries Used

* pandas

## Code Description

1.  **Import pandas:** The pandas library is imported for data manipulation and analysis.
   
2.  **Load the dataset:** The dataset is loaded into a pandas DataFrame.
   
3.  **Data Exploration:**
   * The code displays the first few rows of the dataset.
   * The code determines the shape (number of rows and columns) of the dataset.
   * The code retrieves the column names and their data types.
   * The code provides a concise summary of the dataset, including column names, data types, non-null counts, and memory usage.
4.  **Unique Value Analysis:**
   * The code finds the unique values in the 'Wind Speed' column.
   * The code calculates the number of unique values in each column.
5.  **Weather Condition Analysis:**
   * The code counts the occurrences of each weather condition.
   * The code filters the dataset to find records where the weather condition is 'Clear'.
6.  **Wind Speed Analysis:**
   * The code filters the dataset to find records where the wind speed is 4 km/h.
7.  **Null Value Analysis:**
   * The code calculates the sum of null values for each column.
   * The code calculates the sum of non-null values for each column.
8.  **Data Transformation:**
   * The code renames the 'Weather' column to 'Weather Condition'.
9.  **Descriptive Statistics:**
   * The code calculates the mean of the 'Visibility' column.
   * The code calculates the standard deviation of the 'Press_kPa' column.
   * The code calculates the variance of the 'Rel Hum %' column.
10. **Combined Condition Filtering:**
    * The code filters records based on combined conditions for 'Weather Condition', 'Relative Humidity', and 'Visibility'.
    * The code groups the data by 'Weather Condition' and calculates the mean for other columns.

## Results

* The project successfully analyzed the weather dataset to provide insights into various weather parameters and conditions.
   
* Specific queries were addressed, such as identifying unique wind speed values, counting occurrences of clear weather, and calculating descriptive statistics.

## Code Snippets

### Load Dataset

```python
import pandas as pd
data = pd.read_csv("C:/Users/gvrk1/Downloads/Project+1+-+Weather+Dataset.csv")
