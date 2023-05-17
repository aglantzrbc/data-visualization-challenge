# data-visualization-challenge
Glantz Adam Bootcamp RUT-VIRT-DATA-PT-04-2023-U-LOLC-MWTH - Module 5 Data Visualization

Data Visualization Challenge

TABLE OF CONTENTS
1. Project Description
2. Installation
3. Contributing
4. Acknowledgements

1. Project Description:

In this assignment, we were tasked with using both Pandas and Matplotlib in a real world-type situation to create plots that were subsequently used for analysis.

The specific task of the assignment was to use data science to help the executive board of a fictional pharmaceutical company that specializes in anti-cancer medications. The company recently began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In the company's latest study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of the drug of interest, Capomulin, against the other treatment regimens and assess the results in an executive summary.

Dependencies were made available and the raw data was read in and consolidated into a single DataFrame. The DataFrame was examined and duplicates eliminated. Summary statistics were generated. Bar plots and pie plots were used to display the range of treatment regimens and the sex composition of the mice. Quartiles and the IQR were calculated for the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Potential outliers were identified and were displayed along with the relevant statistics in boxplots. A line plot for the tumor volume across time of a single mouse being treated with Capomulin was generated. A scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen was produced, then the correlation coefficient was determined and a linear regression model was placed over the plot. Findings were considered and analysis provided.

-- OBSERVATIONS FROM THE ANALYSIS ARE PROVIDED AT THE TOP OF THE JUPYTER NOTEBOOK FILE


2. Installation:

This project is coded in Python 3.10.9
The analysis file has an .ipynb extension, so it's meant to be viewed in Jupyter Notebook.

Data files -
    Mouse_metadata.csv
    Study_results.csv

Dependencies -
    matplotlib.pyplot
    pandas
    scipy.stats

-- Note: This project assumes the two source .csv files listed above retain their original names and are in a folder labeled "data" that is one level below where the Python file resides. If you do not follow this relative placement of the elements, either the the program will not run or the path will need to be updated.


3. Contributing:
    Adam Glantz: adamglantz@yahoo.com


4. Acknowledgements:

I consulted with three GitHub repos regarding a very similar data visualization challenge I found through a Google Search:

    Author: Rocky Owens: Houston, TX USA, Jan 2023 = https://github.com/RockyOwens/Pymaceuticals/blob/main/Pymaceuticals_final.ipynb
    Author: Veronika Patel: Dacula, GA USA, July 2021 (www.linkedin.com/in/veronika-patel-09b47326) = https://github.com/patelveronica/Matplotlib/blob/master/Pymaceuticals/pymaceuticals_starter.ipynb
    Author: Ben Anderson: Kansas City, MO USA, Feb 2020 (benjaminpaulanderson@gmail.com) = https://github.com/benanza/Pymaceuticals/blob/master/Pymaceuticals.ipynb