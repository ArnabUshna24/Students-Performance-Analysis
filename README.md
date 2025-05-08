# Students' Performance Analysis


## Overview
This project aims to analyze students' performance in exams and find insights using statistical analysis. It serves the following concerns:

* Retriveing the data from the target location.
* Handling the missing values and outliers (if there is any).
* Performing data visualization.
* Performing basis statistical analyses.


## Data Retrieval
For this project, `Students Performance in Exams.csv` dataset was used, which is available in [Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams). It contains 8 colunmns - `gender`, `race/ethnicity`, `parental level of education`, `lunch`, `test preparation course`, `math score`, `reading score`, and `writing score`. This dataset was loaded into a `pandas` dataframe for further analysis.


## Data Cleaning and Manipulation
To find missing values in the dataset, `isnull` function was used - which showed no missing values. Similarly, outlier identification was performed and outliers were then capped.


## Data Visualization
<table>
  
  <tr>
    <td align="center"><img src="https://github.com/ArnabUshna24/Students-Performance-Analysis/blob/main/data_visualizations/male_female_students_distribution.png" alt="Distribution of Male and Female Students" width="300"/></td>
    <td align="center"><img src="https://github.com/ArnabUshna24/Students-Performance-Analysis/blob/main/data_visualizations/scores_distributions.png" alt="Distribution of Scores" width="300"/></td>
  </tr>
  
  <tr>
    <td align="center"> Fig. 1: Distribution of Male and Female Students </td>
    <td align="center"> Fig. 2: Distribution of Scores </td>
  </tr>
  
  <tr>
    <td align="center"><img src="https://github.com/ArnabUshna24/Students-Performance-Analysis/blob/main/data_visualizations/avg_scores_gender.png" alt="Average Scores by Gender" width="300"/></td>
    <td align="center"><img src="https://github.com/ArnabUshna24/Students-Performance-Analysis/blob/main/data_visualizations/relationship_among_scores.png" alt="Relationship Among Scores" width="300"/></td>
  </tr>
  
   <tr>
    <td align="center"> Fig. 3: Average Scores by Gender </td>
    <td align="center"> Fig. 4: Relationship Among Scores </td>
  </tr>
  
</table>


## Statistical Analyses

<p><strong>Table 1:</strong> Mean, Median and Mode of Scores </p>
<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th> Scores </th>
    <th align="center"> Mean </th>
    <th align="center"> Median </th>
    <th align="center"> Mode </th>
  </tr>
  <tr>
    <td> Math </td>
    <td align="center"> 66.165000 </td>
    <td align="center"> 66.0 </td>
    <td align="center"> 65.0 </td>
  </tr>
  <tr>
    <td> Reading </td>
    <td align="center"> 69.201000 </td>
    <td align="center"> 70.0 </td>
    <td align="center"> 72.0 </td>
  </tr>
  <tr>
    <td> Writing </td>
    <td align="center"> 68.094375 </td>
    <td align="center"> 69.0 </td>
    <td align="center"> 74.0 </td>
  </tr>
</table>


<p><strong>Table 2:</strong> Standard Deviation of Scores </p>
<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th> Standard Deviation </th>
    <th align="center"> Math </th>
    <th align="center"> Reading </th>
    <th align="center"> Writing </th>
  </tr>
  
  <tr>
    <td> Math </td>
    <td align="center"> 14.922414 </td>
    <td align="center"> 14.503481 </td>
    <td align="center"> 15.068368 </td>
  </tr>
  
</table>


<p><strong>Table 3:</strong> Gender-wise Performance </p>
<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th> Scores </th>
    <th align="center"> t-statistic </th>
    <th align="center"> p-value </th>
    <th align="center"> Significance </th>
    <th align="center"> Interpretation </th>
  </tr>
  
  <tr>
    <td> Math </td>
    <td align="center"> 5.31 </td>
    <td align="center"> 1.35 × 10⁻⁷ </td>
    <td align="center"> Significant </td>
    <td align="center"> Male students likely score higher </td>
  </tr>

  <tr>
    <td> Reading </td>
    <td align="center"> -8.02 </td>
    <td align="center"> 2.99 × 10⁻¹⁵ </td>
    <td align="center"> Significant </td>
    <td align="center"> Female students likely score higher </td>
  </tr>

  <tr>
    <td> Writing </td>
    <td align="center"> -10.06 </td>
    <td align="center"> 9.48 × 10⁻²³ </td>
    <td align="center"> Significant </td>
    <td align="center"> Female students likely score higher </td>
  </tr>
  
</table>


## Build from Source
Instructions are provided in the `ipynb` file.


If you have any queries, contact me: arnabnushna24@gmail.com
