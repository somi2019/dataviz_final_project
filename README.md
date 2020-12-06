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

![04](https://user-images.githubusercontent.com/70166302/100644982-087c8580-330a-11eb-9ed0-b9899611c1bd.png)
Again we see there is a *gender gap* between male and female. on average male run faster than female. 
This gap is greater among the runners who finish sooner than among those who finish last.
The peak finish time for male crossed finished line was in *13237 sec*  and *14825 sec* for female.  

![05](https://user-images.githubusercontent.com/70166302/100645235-627d4b00-330a-11eb-9e1d-340ca300db1d.png)
This plot shows *overall rank* of a runner with its *gender* in finishing time of less than *9000* seconds*.
First one is a male who finishes in 7750 seconds and the first fast female runner finishes at *8600* seconds and her rank is *21th*.

![06](https://user-images.githubusercontent.com/70166302/100647001-dae50b80-330c-11eb-8463-548e04a2c21a.png)
There is a *correlation* between finishing time and half time finishing in **USA**.

![07](https://user-images.githubusercontent.com/70166302/100647207-2ac3d280-330d-11eb-98de-ef5068a2716e.png)
Filtering the first *20* runners,then plot overall ranks of them versus finishing time.First runners finish it in *7777 seconds*,second one in 20 seconds later. The last one in *8418 seconds*,so they really finish the race in a very close range.

![08](https://user-images.githubusercontent.com/70166302/100650732-5eedc200-3312-11eb-8e04-3234457ad9e4.png)
Above plot shows countries which have youngest runnersunder *25* years old,as it is obvious USA with *1666* young runners has the most youngest runners among other countries. with a huge difference canada is the second country with *43* young runners under 25 years old.

![09](https://user-images.githubusercontent.com/70166302/100650966-c0159580-3312-11eb-8fc2-ca4f1f138f7c.png)
In above map 3 first most popluted runneres countries are shown:*USA,Canada,United Kingdom*.

![10](https://user-images.githubusercontent.com/70166302/100651562-9f9a0b00-3313-11eb-875f-c3b22876aab1.png)

![11](https://user-images.githubusercontent.com/70166302/100651750-ee47a500-3313-11eb-9c15-c6c4e856ba69.png)

![12](https://user-images.githubusercontent.com/70166302/100651869-20f19d80-3314-11eb-9678-2b0c04944117.png)


# conclusion
I chose this dataset because when I was studying my bachelor I joind marathon group of my previous university and I had a memorable time those days.So his dataset could decode some new aspects of this sport for me in other countries.
I started ploting some basic plot at first to have a general opinion about the whole topic,then shifted to some interactive plot and finally some spatial plot.bellow you can find some interesting issues which I found from these plot:

* The *youngest female* finishers were **18** years old, and *oldest female* ones were **84** years old.

* *youngest male* finishers were 18 years old and *oldest male* runners were **83** years old.

* Women are more eager to marathon when they are younger,specially when they are **25** and again when they are around **40**,but as they becoe older,they lose eagerness to run.

* Men become interested to marathon slow by slow when they become older,specifically when they become **40,45,50** they love to join marathon races.after turning to **50** always more number of men are interested to run compare to women.

* *Female runnersare younger than male runners* in first quartile, median and third quartile.Median for women is at their **40** but for men is at their **45**.

* Average time of finishing the race for women is more than men,also the women who end the race are younger compare to men.

* Age is really important!as you see when people are between **20 to 40** years old average finishing time is much less compare to when they become older.

* Men finish  marathon race sooner than women.Specially when they are so old (after 70 years old) men run more faster than women.

* There is a *gender gap* between male and female. On average male run faster than female. This gap is greater among the runners who finish sooner than among those who finish last.

* The peak finish time for male crossed finished line was in **13237** sec  and **14825** sec for female.

* For only 3 selected country **(Japan,Canada,Italy)** from 3 different continent,gender distrubition in different finishing times,most of the men run in 12800 seconds while most of the women run in 13400 seconds.

* For finishing time of less than **9000** seconds,First one is a male who finishes in **7750** seconds and the first fast female runner finishes at **8600** seconds and her rank is 21th.

* There is a high correlation of *0.903* between finishing time and halfway time in USA for maraton runners.As halfhway time increases so does finishing time.

* Filtering the first **20** runners,first runners finish it in **7777** seconds,second one in *20* seconds later. The last one in **8418** seconds,so they really finish the race in a very close range.

* In countries which have youngest runnersunder **25** years old,as it is obvious USA with **1666** young runners has the most youngest runners among other countries. with a huge difference canada is the second country with **43** young runners under 25 years old.

* Calculating the number of participants in every country (using count function) shows that *USA* has the first rank of participants with **20945** runners with huge difference even with the second country which *Canada* with *1870*.
Some countries only had **1** participant such as *Falkland Islands*,*Bulgaria* and *Jamaica*.

* 3 first countries with most poplution of runneres are shown in one of spetial map:*USA with 20945,Canada with 1870 and *United Kingdom with 425*paticipants were most active countries in this sport at *2017*.


* Then Young Faster Runners Population in every country was checked and again *USA* with **66** runners under **40** was the first ranked country.

* After filltering the male runners to check the gender balance of this race,it shows that for countries such as  *USA* and *Canada* there is a fair gender balance.

* Finally I was really curious to know how is the trend of old women(more than 50s) in participating in marathon sport,and it was intersting to see this distrubution in different countries,again *USA* with **1887** female participants has the first ranking of this category.


## Project 03
In this exercise you will explore methods to visualize text data and practice how to recreate charts that show the distributions of a continuous variable. 


## Part 1: Density Plots

Using the dataset obtained from FSU's, for a station at Tampa International Airport (TPA) from 2016 to 2017,some charts shown below were created:

## Part 2: Visualizing Text Data
for this section *BB_top100_2015* data set was selected and one of the charts could be seen here:
