---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "NBA Advanced Shooting Stats"
date: 2023
published: true
labels:
  - Python
  - Data & Statistics
  - Data Scraping 
summary: "I created a program that scrapes data from two different charts and combines them, but only retriveing the data from players who meet certain metrics and conditions. "
---
<img width="800px" src="../img/Stats1.jpg" >
<div class="text-center">
  <img width="800px" src="../img/Stats3.jpg" >
  <img width="800px" src="../img/Stats2.jpg" >
</div>

I made a program that retrieves NBA Per Game and Shooting statistics of all current NBA players. First, it scrapes data from two different sets of different charts – one set is for general stats players put up per game (Points Per Game, Assists Per Game, Rebounds Per Game, etc.), and the other is for advanced specified shooting statistics such as where they're shooting from and how often.
Of course there are hundreds of NBA players some more relevant than others (respectfully), so I have it in my program to filter out any player who plays less than 20 minutes Per Game. In the end, the program merges these two sets of Charts into one, so I have all the important info in a single place. Finally, it saves this combination of data into one Excel file that updates automatically every Sunday. 

Here is some example code to illustrate Simple Schema use:

{% gist 84dc22d2d080d2f728cf55347becd4aa %}
