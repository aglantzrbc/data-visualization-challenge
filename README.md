# data-visualization-challenge
Glantz Adam Bootcamp RUT-VIRT-DATA-PT-04-2023-U-LOLC-MWTH - Module 5 Data Visualization

Data Visualization Challenge

Overview of project:

In this assignment, we were tasked with using both Pandas and Matplotlib in a real world-type situation to create plots that were subsequently used for analysis.

Explain the purpose of this task:

The purpose of the assignment was to use data science to help the executive board of a fictional pharmaceutical company that specializes in anti-cancer medications. The company recently began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In the company's latest study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of the drug of interest, Capomulin, against the other treatment regimens and assess the results in an executive summary.

Dependencies were made available and the raw data was read in and consolidated into a single DataFrame. The DataFrame was examined and duplicates eliminated. Summary statistics were generated. Bar plots and pie plots were used to display the range of treatment regimens and the sex composition of the mice. Quartiles and the IQR were calculated for the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Potential outliers were identified and were displayed along with the relevant statistics in boxplots. A line plot for the tumor volume across time of a single mouse being treated with Capomulin was generated. A scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen was produced, then the correlation coefficient was determined and a linear regression model was placed over the plot. Findings were considered and analysis provided.

OBSERVATIONS FROM THE ANALYSIS ARE PROVIDED AT THE TOP OF THE JUPYTER NOTEBOOK FILE

Dependencies:

    matplotlib.pyplot
    pandas
    scipy.stats

This project assumes the two source csv files retain their original names and are in a folder labeled "data" that is one level below where the Python file resides. If you do not follow this relative placement of the elements, either the the program will not run or the path will need to be updated.

Sources consulted:

The work in this assignment is my own, but I consulted with three GitHub repos regarding a very similar data visualization challenge I found through a Google Search:

    Author: Rocky Owens: Houston, TX USA, Jan 2023 = https://github.com/RockyOwens/Pymaceuticals/blob/main/Pymaceuticals_final.ipynb
    Author: Veronika Patel: Dacula, GA USA, July 2021 (www.linkedin.com/in/veronika-patel-09b47326) = https://github.com/patelveronica/Matplotlib/blob/master/Pymaceuticals/pymaceuticals_starter.ipynb
    Author: Ben Anderson: Kansas City, MO USA, Feb 2020 (benjaminpaulanderson@gmail.com) = https://github.com/benanza/Pymaceuticals/blob/master/Pymaceuticals.ipynb

Student: Adam Glantz 571-232-9753 adamglantz@yahoo.com 20230514pm