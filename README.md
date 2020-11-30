# Data Visualization and Reproducible Research

> Somayeh Sadeghizadeh 

Learn more about me in my [GitHub profile page](https://github.com/reiminer)


The following is a sample of products created during the _"Data Visualization and Reproducible Research"_ course in Fall 2020.


## Project 01


## Data Visualization Course Project

## WorldCupMatches

For this mini project I worked on world cup matches dataset, which includes matches during **1930 to 2014** held in different cities between different teams I focouced on some of variables mainly like *Home team goals*, *away team goals*, *audience* and some other variable to be used was created for this report such as *total goals*. Here I put some main Visualization of my project in this file:

![11](https://user-images.githubusercontent.com/70166302/99699013-7b127900-2a5f-11eb-8ac9-471b6d6372aa.jpeg)


* Total Goals Distrubution:

Distribution of *Total Goals* using the *hist()* function. We can see in the graphs that the data is skewed to the right.

![2](https://user-images.githubusercontent.com/70166302/99691907-b610ae80-2a57-11eb-9108-f726feacd8dd.png)



*	Attendance in Home Town:

Attendance in cities like *London* and *Mexico City* and *Los Angeles* were more than other cities for, to be more specific I filtered number of  audiences  between *70,000 to 150,000* and used the function of *facet_wrap* to separate cities.

![12](https://user-images.githubusercontent.com/70166302/99699679-376c3f00-2a60-11eb-8a6e-c802c31fc6fd.png)

*	Attendance VS. Home Team Games (More than *50000* attendance):

Another format for checking games with high number of audiences for hometown games filled with total goals, *Brazil and Mexico* had most audiences in home town matches.

![5](https://user-images.githubusercontent.com/70166302/99691923-bad56280-2a57-11eb-99db-4b0a2359a4d3.png)

*	Attendance of Winning Teams with the Location of Game: 

This plot shows relationship of attendance vs winning teams and the location of matches, colored disceretly,also in *Netherland* match there were fewest attendance to watch the game.

![6](https://user-images.githubusercontent.com/70166302/99691929-bc068f80-2a57-11eb-947b-2b53e66ace3a.png)


*	Attendance vs. Date: Plot shows relation of attendance versus the year the match was held, it is also colored by winning team, using the *scale_colour_iwanthue()* function and *palette of hues* which has lots of colors for qualitative variable. *Italy* in *1970* has the most audiences more than *100,000* people.

![7](https://user-images.githubusercontent.com/70166302/99691933-bd37bc80-2a57-11eb-94d6-26bb08d2608d.png)

*	Away team goals vs. Home team goals in USA: 

To check one country situations specifically *USA* home team goals vs. away team goals was considered, there were 5 away team goals for *Czechoslovakia* and 1 home team goals for *USA*, also 3 goals for *USA* and 0 for *Paraguay*, this way we can check every country more specifically. For writing on the plot, used annotate function and *geom_label_repel* to have rectangle labels.

![8](https://user-images.githubusercontent.com/70166302/99691942-bf018000-2a57-11eb-84e9-fa07fa11ffef.png)

*	Total goals in *USA* matches over the years:

To continue focusing on one specific country, using *geom_point* it can be seen than during the year’s total goals of a match to be more obvious I used *facet wrap function* to show the away team player. For instance, in play with *Czechoslovakia* there were total of *6* goals in *1990*.

![Picture10](https://user-images.githubusercontent.com/70166302/99696066-45b85c00-2a5c-11eb-8a69-39443500c7b5.png)


## Conclusion:

•	According to histograms of Attendance and Total Goals as we see skewness in first plot, so if we want to have more specicific result, it is better to normalize them at first then work on data.

•	For audiences between 70,000 to 150,000 Number of attendance in cities like **London** and **Mexico City** and **Los Angeles** were the most in home town matches.

•	For More than **50,000** attendance Teams of **Brazil** and **Mexico** had most audiences in home town matches.

•	For audiences more than **90,000** for games with 2 goals there were the most attendances in **Rio De Janiro**.Also in **Netherland** match there were fewest attendance to watch the game.

•	**Italy** in **1970** has the most audiences more than 100,000 people.

•	specifically for **USA** home team goals vs. away team goals was considered, there were 5 away team goals for **Czechoslovakia** and 1 home team goals for a **USA**, also 3 goals for **USA** and 0 for **Paraguay**.






## Project 02

# Mini Project(**marathon result 2017**)
---
This *mini project* will review marathon result dataset in different countries in 2017,with some main variables such as gender,age,overal ranking,city,country which I worked on them mainly also some other variable to be used created for this report such as finishing time.

![01](https://user-images.githubusercontent.com/70166302/100644005-bf780180-3308-11eb-88ff-f99a7cde01c4.png)
It seemes women are more eager to marathon when they are younger,specially when they are *25* and again when they are around *40*,but as they becoe older,they lose eagerness to run,but in reverse men become interested to marathon slow by slow when they become older,specifically when they become *40,45,50* they love to join marathon races.after turning to *50* always more number of men are interested to run compare to women.

![02](https://user-images.githubusercontent.com/70166302/100644274-1d0c4e00-3309-11eb-9964-91bf22a04bc7.png)
Intersting point in this plot is *Female runnersare younger than male runners* in first quartile, median and third quartile.Median for women is at their 40 but for men is at their *45*.

![03](https://user-images.githubusercontent.com/70166302/100644663-9e63e080-3309-11eb-9969-68ffe36f606c.png)
This plot shows that if we like or dislike , **age**is really important!
As you see when people are between *20 to 40* years old average finishing time is much less compare to when they become older.
Second interesting point is that usually in all periods of life men finish a marathon race sooner than women.Specially when they are so old *(after 70 years old)* men run more faster than women.
## Project 03

In this project, I explored ... _[short description of your revised project goes here]_

**Sample data visualization:** 

_[include your favorite visualization from this project here]_
<img src="https://github.com/reisanar/figs/raw/master/jackie_jessie_marion.png" width="80%" height="80%">


### Moving Forward

_add here a short reflection on what you learned and what you plan to continue exploring in terms of data visualization, data storytelling, reproducible research, and/or related topics_
