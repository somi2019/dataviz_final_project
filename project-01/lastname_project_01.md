---
title: "Mini-Project 01"
output: 
  html_document:
    keep_md: true
    toc: true
    toc_float: true
---


# Data Visualization Project 01

# Somayeh Sadeghizadeh
# Email:ssadeghizadeh8676@floridapoly.edu

---
# Mini Project:

For this *mini project* I worked on world cup matches dataset, which includes matches during 1930 to 2014 held in different cities between different teams with some main variables which I worked on them mainly such as Home team goals, away team goals, audience also some other variable to be used created for this report such as total goals.

# Analysis:
## After making data tidy,we start to analyse the data:

* **Audiences Distribution**: After making data tidy, I started analysis of data by drawing a *histogram* of audiences: We can see in the graphs that the data is skewed to the right.
* **Total Goals Distribution**: Checking the distribution of total goals using the *hist () function*. We can see total goals in the graphs are skewed to the right.
* **Boxplot**: Checking *median* and *outliers* for home team goal box variable through boxplot for 3 different variables.


Checking the distribution of both the variables using the hist() function. We can see in the graphs that the data is *skewed to the right*.

Checking the distribution of both the variables using the hist() function. We can see total goals in  the graphs are *skewed to the right*.


Checking median and outliers for total box variable through boxplot.the **median** for this variable is around 3 goals and outliers starts from 9 goals.




Checking median and outliers for home team goal box variable through boxplot.the **median** for this variable is 2 goals and outliers starts from 7 goals.



Checking median and outliers for Away team goal box variable through boxplot.the **median** for this variable is 1 goals and outliers starts from 7 goals.


* **Total Goals in Hometown**: to see *median* and *outliers* for every home team matches, in another plot I used *boxplot* and *geom_jitter*.to see the details more obvious.


* **Attendance in Home Town** : to show Drawing number of attendances in home team matches in different cities, attendance in cities like **London** and **Mexico City** and **Los Angeles** were more than other cities for, to be more specific I filtered number of audiences between 70,000 to 150,000 and used the function of 

* **Attendance VS. Home Team Name (More than 50000 attendance)**: Another format for checking games with high number of audiences for hometown games filled with total goals, in **Brazil** and **Mexico** had most audiences in home town matches.


* With mutate function winning team variable is created to check some more items:



* **Attendance of Winning Teams with the Location of Game**: This plot shows relationship of attendance vs winning teams and the location of matches are colored disceretly,also Netherland match there were fewest attendance to watch the game.


* **Attendance VS. Total Goals**: To see more details, filtered number of audiences for more than 90000 people and checked it versus number of total goals with the label of city on the games.as it can be seen for 2 goals games there were the most attendances in **Rio De Janiro**, using the label of cities on the plot.


* **Attendance vs. Date**: Plot shows relation of attendance versus the year the match was held, it is also colored by winning team, using the scale_colour_iwanthue() function and  palette of hues which has lots of colors for qualitative variable. **Italy** in *1970* has the most audiences more than *100,000* people.



* **Away team goals vs. Home team goals in USA**: to check one country situations specifically **USA** home team goals vs. away team goals was considered, there were 5 away team goals for **Czechoslovakia** and 1 home team goals for USA, also 3 goals for USA and 0 for **Paraguay**, this way we can check every country more specifically. For writing on the plot, used annotate function and geom_label_repel to have rectangle labels.


* **Total goals in USA matches over the years**: To continue focusing on one specific country, using geom_point it can be seen than during the year’s total goals of a match to be more obvious I used facet wrap function to show the away team player. For instance, in play with **Czechoslovakia** there were total of 6 goals in *1990*.


* **Home Team Goals for winning team**: graph number of total goals are shown versus to winning team names,in matches which **Brazil** had played as one side there were lots of goals.
 
# Conclusion:

* According to histograms of Attendance and Total Goals as we see skewness in both plot,so if we want to have more specicific result,it is better to normalize them at first then work on data.
* Acoording to boxplot plots outliers for home team and away team goals are *7* and for total goals are *9* that should be considered in our analysis.
* Teams of **Brazil** and **Hungary** had the most *Total Goals* in home town matches.
* For audiences between *70,000 *to *150,000* Number of attendance in cities like **London** and **Mexico City** and **Los Angeles** were the most in *home town* matches.
* For More than *50,000* attendance Teams of **Brazil** and **Mexico** had most audiences in home town matches.
* For audiences  more than *90,000* for  games with 2 goals there were the most attendances in **Rio De Janiro**.
* **Italy** in *1970* has the most audiences more than *100,000* people.
* specifically for **USA** home team goals vs. away team goals was considered, there were 5 away team goals for **Czechoslovakia** and 1 home team goals for USA, also 3 goals for USA and 0 for **Paraguay**.
* In matches which **Brazil** had played as one side there were lots of goals.

