
<h1 align="center">Data Science & Machine Learning : R Tropical Storms Analysis <p align="center"></h1>

<h1 align="center">Bar Bettash<p align="center">
<a href="https://www.linkedin.com/in/barbettash/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
</h1>


<!-- ABOUT THE PROJECT -->
## About The Project
This project analyzes a dataset of tropical storms using R. It explores various aspects of the storms, including their frequency, intensity, and geographical distribution. The analysis includes data exploration, visualization, and statistical summaries to gain insights into tropical storm patterns and characteristics.

### Built With

![image](https://github.com/user-attachments/assets/2c2c5126-d4e8-4375-8e30-c8db6bd4e019)

<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

To run the project, you need the following libraries installed:

* tidyverse: A collection of R packages for data science, including ggplot2, dplyr, and more.
  ```sh
  install.packages("tidyverse")

* readxl: For reading Excel files into R.
  ```sh
  install.packages("readxl")

### Load dataset:

The tropical storms dataset is loaded from an Excel file named "tropical_storms.xlsx" using the read_xlsx function from the readxl package.

### Project Structure:

The project includes several analyses:

* Storm Count:Counting the number of unique storms in the dataset.

* Category 5 Storm Frequency: Investigating the time since the last Category 5 storm.

* Storm Indexing: Adding an index to storms based on their names.
 
* Data Visualization: Creating various plots to visualize storm data.
 
* Storm Characteristics Analysis: Summarizing key storm characteristics by year and category.
 
* Latitude Changes: Identifying category with the largest increase in observations below latitude 30.
 
* Storm Category Distribution: Visualizing the distribution of storms across categories.
 
* Monthly Storm Patterns: Examining storm patterns by month.
 
* Wind vs. Pressure Relationship: Analyzing the relationship between wind speed and pressure for each storm category.
  
* Impact Analysis: Conducting a hypothetical impact analysis based on wind speeds and hurricane radius.
