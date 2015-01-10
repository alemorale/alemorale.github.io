---
layout: post
title: "Analyzing Red Cross's Disaster Responses"
date: 2012-06-01
categories: data-analysis retro
tags: matlab, data-analysis
---

The following is an analysis I performed during the Chicago *Data Dive* organized by [DataKind](http://datakind.org). 

A *Data Dive* is an event where  analysts and data scientists alike help non-profit organizations solve problems with data over the course of a weekend. I worked with a team helping the Red Cross.
<br>

The American Red Cross provide a variety of services: response to disasters, health and safety information to blood collection, among others. They also collect tremendous amount of data. With such an amount of data it came as no surprise that they had problems keeping track of the data and they lacked a comprehensive overview of their data.

In other words, they were missing out on the story their data could be telling them. And, as with any organization with limited resources, this is a fundamental question. For example, where should the Red Cross allocate resources to prevent disasters? 

For the sake of this excercise we concentrated our analysis to disaster emergengy responses (mostly fire related). After gathering, cleaning and munging some data, we found that fires are often clustered in certain neighborhoods, providing insight on where the organization could more effectively allocate fire prevention efforts. As a no surprise, we found a strong correlation between disaster responses and per capita income, race, and population.

Over 30% of reported fires happen within 10 zipcode zones!


<!--{:.image-size} -->
![Total responsess by zipcode]({{site.baseurl}}/assets/red-cross-zipcodes.png) 

 
The following map shows the zipcode zones with highest reported disasters. 
<!--
The Chicago chapter of the American Red Cross did not have, at the time, a centralized database of 
-->

<!--<iframe width="600" height="400" scrolling="no" frameborder="no" -->
<iframe scrolling="no" frameborder="no" src="https://www.google.com/fusiontables/embedviz?q=select+col39+from+1WzNoQKJMQQgFMPimFMtf602iUhZSUvDfncPP4M0&amp;viz=MAP&amp;h=false&amp;lat=41.79197187093165&amp;lng=-87.69969750781252&amp;t=1&amp;z=9&amp;l=col39&amp;y=2&amp;tmplt=2&amp;hml=GEOCODABLE"></iframe>


<br> <br>
This analysis was part of a *Data Dive* organized by [DataKind](http://datakind.org). You can look 
[here](http://www.shareable.net/blog/datakinds-vision-of-a-data-driven-social-change-movement) for more information about that event.