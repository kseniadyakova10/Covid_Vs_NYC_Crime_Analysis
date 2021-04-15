### Summary 
The focus of the project is to understand the effects of the COVID-19 pandemic on crime rates in New York City. Using public crime data, we analyzed trends to determine which types of crimes became more common due to the shutdown and which types of crimes became less common based on YOY trends. 

### Specific Questions 
1. What are the top 15 crimes in March, April and May of 2019 and 2020?
2. What specific crimes have increased 
3. What specific crimes have decreased 
4. Is there a relation between positive Covid counts and arrests? 
5. How do the trends vary by age range? 

### Data Cleanup 
Three biggest files we worked with were NYPD Arrest Data Year to Date(2019 extraction),NYPD Arrest Data Historic(2020 extraction) and NYPD Hospitalization Counts. Since we only needed two specific years, we were able to extract those years and work with much smaller files for our analysis.
![Data_cleanup](https://github.com/kseniadyakova10/Covid_Vs_NYC_Crime_Project/blob/main/Images/data_cleanup.png?raw=true)

### Top 15 crimes analysis
Starting focus was on months of March, April and May for 2019 and 2020. Obsdervation was made that some of the crimes of 2019 became much less popular in 2020 and vice versa.
![Top 15](https://github.com/kseniadyakova10/Covid_Vs_NYC_Crime_Project/blob/main/Images/top_15_crimes.png?raw=true)

### YOY % change in Crime Rate
After observing some movement in top 15 crime analysis, we wanted to see if there is an overall change across all crimes and how big of a change, if any.
![YOY change](https://github.com/kseniadyakova10/Covid_Vs_NYC_Crime_Project/blob/main/Images/change_crime_rate_yoy.png?raw=true)

### Age group analysis
Focusing in on age groups of 18-24 and 25-44, assault, drugs and larceny were most common crimes of both age groups. However, there is a huge increase in 25-44 age group in year 2019.
![2019 age group](https://github.com/kseniadyakova10/Covid_Vs_NYC_Crime_Project/blob/main/Images/age_group_2019.png?raw=true)

In 2020, there is a big drop as far as the amount of crimes committed within both age groups. Although 25-44 are still in the lead. Also, it seemes that robbery became more popular among 18-24 year olds opposed to larceny among 25-44 year olds.
![2020 age group](https://github.com/kseniadyakova10/Covid_Vs_NYC_Crime_Project/blob/main/Images/age_group_2020.png?raw=true)

### Covid-19 vs Arrests analysis
Our final analysis was made on rates of Covid-19 case, death and hospitalization count vs NYPD arrest count. We wanted to see if there was any kind of relationship between them. Although the analysis was only made for month of March, there was no relationship observed. So it was decided unnecessary to continue and move on.
![Covid vs Arrest](https://github.com/kseniadyakova10/Covid_Vs_NYC_Crime_Project/blob/main/Images/covid_vs_arrest.png?raw=true)

### Datasets explored:
* https://data.cityofnewyork.us/Social-Services/NYPD/fjn5-bxwg
* https://data.cityofnewyork.us/Social-Services/NYPD/fjn5-bxwg
* https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc

### Team Members
* Ksenia Dyakova, Phoebe Yaheng Wu, Cesar Serrano, Megan Gebhart, Adriana Cieslak
