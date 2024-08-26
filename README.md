# Readme

## Content
1) Motivation for the project
2) Files in the repository
3) Summary of the results of the analysis
4) Libraries which are used

### Motivation for the project
- Since I'm interested in purchasing a boat at the lake of constance, I am interested in the gerneal trend for boats in Germany as well as the trend at the lake of constance and where to buy them at a good rate.
- In the project I will answer to the following three questions
	- What are the three most offered engine boats in Germany and what specifications do these boats have?
	- What sells best at the Bodensee (lake of constance)?
	- Where are these boats cheapest to buy in Germany?

### Files in the repository
- For this task a data set is taken into account of engine boat sell offers in Europe + Swizerland and some other countries from a marketing team. The data set includes 10 categories: Price, Boat Type, Manufacturer, Type, Year Built, Length, Width, Material, Location and Number of views last 7 days. This is a good starting point for investigating the most favoured boats on the lake of constance ant where to buy them the cheapest in Europe.The Source of data is: https://www.kaggle.com/datasets/karthikbhandary2/boat-sales?resource=download
- The implementation can be found in CRISP-DM_process. The .ipynb contains the implementation and the .html contains the implementation as well as a web readable format.
- boat_data.csv is the source of data where this project is build on.
- boat_data_cleaned_countries_splitted.csv is an cleaned and feature edited version of boat_data.csv which is used for the analysis in the project.

### Summary of the results of the analysis
- The most popular engine boats for the Bodensee can be bought at the lowest price in Rheinland-Pfalz and Nordrhein-Westfalen. Important to state is that there are spcial regulations regarding emissions and grey water for boats at the Bodensee (lake of constance). This can lead to further investments to get a boat licensed for the lake of constance. This furhter costs could not taken into account in this data set because there are no such information in the data set about the boats.

### Libraries which are used
- numpy 
- pandas
- matplotlib.pyplot 
- sklearn OneHotEncoder
- csv
