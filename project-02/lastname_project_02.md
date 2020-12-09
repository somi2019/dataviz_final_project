---
title: "Mini-Project 02"
output: 
  html_document:
    keep_md: true
    toc: true
    toc_float: true
---

# Data Visualization Project 02

> Somayeh Sadeghizadeh 

## Mini-Project 2

This data set was selected because when I was studying my bachelor I joind marathon group of my previous university and I had a memorable time those days. This dataset decoded some new aspects of this sport to me in other places of world.
I started ploting some basic plot at first to have a general opinion about the whole topic,then shifted to some interactive plot and finally some spatial plot.

![30](https://user-images.githubusercontent.com/70166302/101683436-f0f07b80-3a32-11eb-9990-f9ca70cfac53.png)

![31](https://user-images.githubusercontent.com/70166302/101683438-f1891200-3a32-11eb-886c-365ef1ca87ae.png)

![32](https://user-images.githubusercontent.com/70166302/101683440-f221a880-3a32-11eb-8477-ae93672fa88c.png)

![33](https://user-images.githubusercontent.com/70166302/101683445-f2ba3f00-3a32-11eb-9a06-bd83bb0cde1e.png)

![34](https://user-images.githubusercontent.com/70166302/101683446-f352d580-3a32-11eb-953c-ee42992a8d54.png)

![35](https://user-images.githubusercontent.com/70166302/101683448-f352d580-3a32-11eb-990d-36253d298980.png)

![36](https://user-images.githubusercontent.com/70166302/101683449-f3eb6c00-3a32-11eb-9352-b9e34c938444.png)

![37](https://user-images.githubusercontent.com/70166302/101683452-f3eb6c00-3a32-11eb-8198-481bff3212d4.png)

![38](https://user-images.githubusercontent.com/70166302/101683454-f3eb6c00-3a32-11eb-9c48-2fe1ce93bc69.png)

![39](https://user-images.githubusercontent.com/70166302/101683456-f3eb6c00-3a32-11eb-93b0-a3735e0c811f.png)

![40](https://user-images.githubusercontent.com/70166302/101683459-f4840280-3a32-11eb-90ee-ca9cc05a27fe.png)

![41](https://user-images.githubusercontent.com/70166302/101683463-f4840280-3a32-11eb-945f-93e0128f536d.png)

![42](https://user-images.githubusercontent.com/70166302/101683465-f51c9900-3a32-11eb-8d52-4849ae31afee.png)



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



# Principles of data visualization:

## Geometrics:

Different type of plots were created including:histogram,scatterplot,coloumn bar,density,box plot to visualize different aspects of this dataset.

## Design:

* Gestalt Principles tried to be considered specially items such as proximity,similarity,continuty and closure.

* The Big Four: CRAP

 1. Contrast*: make different by different fonts and color.

 2. Repetition*:Repeat visual elements (colors, fonts, shapes) to create a strong unified theme.

 3. Alignment*: try to have a visual connection among items in the plots

 4. Proximity*: group related items


## Aesthetics: 

* Using some functions such as *theme() function* with installing *ggthemes* package to create different type of theme for every plot.

* Customizing the look with *coord_cartesian* and defining x and y limit for our plot.Flipping the axis with *coord_flip()* and *geom_label_repel* to add label to plot.Finally I used  *annotation* to add specific point of the chart when was useful.
* Dodging preserves the vertical position of an geom while adjusting the horizontal position. *position_dodge()* requires the grouping variable to be be specified in the geom.
* *scale_x_continuous* is a tool for scales of having continuous x axis aesthetics.*breaks* is an integer guiding the number of major breaks on the x axis.
* modify the title of graphs with *plot.title* function and using face and size to modify format of title.Also modify tilte location with *hjust*

## Color Palettes: 

* Using some different color pallet to emphasize on important sections and results.

* I tried to use *bright or dark colors* to highlight information that requires greater attention.in this dataset there was a unordered categorical *(gender)* required distinct colors that will not be easily confused with one another.

* Moreover, whenever I needed a special color a *Hexadecimal* color was used.



## Interactive Map:

I really like these type of map,tried to have the function of  *ggplotly()* for most of the plot,as it gives me really a better perceive of data in detail.Also you can zoom by selecting an area of interest and hover the line to get exact value of an area.


## Spatial Map:

*  Drawing spetial plot was challenging for me at first and I got many guidance from Dr.Sanchez,but after being able to a variety of plots their interpretation was interesting for me, also as abbraviation of countries names were avialable,package of *rnaturalearth* was used and by using function of *leftjoin* dataframe of *marathon_2017* and datashape of *world* were joined to eachother.














