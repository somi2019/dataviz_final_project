---
title: "Visualizing Text and Distributions"
output: 
  html_document:
    keep_md: true
    toc: true
    toc_float: true
---

# Data Visualization Project 03


In this exercise some methods were explored to visualize text data and practice how to recreate charts that show the distributions of a continuous variable. 


## Part 1: Density Plots

Using the dataset obtained from FSU's, for a station at Tampa International Airport (TPA) from 2016 to 2017, attempt to recreate the charts some charts.

![weather foreast](https://user-images.githubusercontent.com/70166302/101291625-32d1b580-37d8-11eb-87c9-7e4f9bb7cc4e.jpg)

 Bellow you can find one of my favorite charts in this case:
 

![](lastname_project_03_files/figure-html/unnamed-chunk-5-1.png)<!-- -->



## Part 2: Visualizing Text Data

Second part of this practice is about Visualizing Text Data topic,choosing **Billboard Top 100 Lyrics**, some plots were created,
![top-10-songs](https://user-images.githubusercontent.com/70166302/101291779-44678d00-37d9-11eb-9bd6-ba9ddc49d305.png)

one of intersting plots can be seen here:

![](lastname_project_03_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

# Conclusion
In this project, after checking the basics features and performing some actions such as data cleansing and removing uninformative words,an exploratory analysis was begun to categorize song levels.

Next,text visualizing was checked by unnesting lyrics into tokenized words so it was possible to look at lyric complexity. The results provide critical insights for the next steps of **sentiment analysis** and topic modeling.

Finally,**TF-IDF analysis**  was used to represent the information behind a word in a document relating to some outcome of interest. Result may look interesting, but it could be only some part od the whole story.
* use of **slice(seq_len(n))** to grab the first n words in each chart_level. 
* use **bind_tf_idf()** to run the formulas and create new columns.
