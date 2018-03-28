This project analyzes some data about homelessness in the USA.  I work at a homeless shelter so I thought that this would be applicable to me and that I would understand the data that I was seeing.
Couple of things to know about the data. First, if you see CoC that means Continuum of Care which essentially is a jurisdiction, like a city or group of counties.  Second, the data gets better over time and they break it out into more and more categories.  However, I only looked a the total people who were added up each year for each of the CoCs, over the 10 years.
Some things to know about the project. I used SQLite and I wrote the code in Jupyter Notebooks.  I had to import the csv and sqlite3 libraries.  I also used bokeh to visualize and pandas to pivot some of the data so that it could be easily viewed in on a table.  

In order to see what you need to see, you should just click on the “Cells” and then “Run all”. It should open a browser and show you a graph.  The second to last cell should then show you a table.  The top five lines on that table are the five lines that are represented on the graph.

What was asked and what was found.  I found the largest decrease of homeless in all the CoCs in the USA over 10 years.  I figured that it could be inferred that those 5 CoCs were doing something right and it might be interesting to do some research on the practices of those CoCs and then maybe use those methods in CoCs that struggled more to reduce their homeless populations.  You can see that a Detroit, two Texas, one California, and one Georgia CoC made it to the top of the list.

Also interesting, but not what I was actually trying to find, any of the ranges (far right value) at toward the bottom of the table that have negative numbers actually show a homeless population increase.  I can guess that some of these may be due to many people moving to those areas, but it would be interesting to look into that more.
 
