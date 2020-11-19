# somi-2019
this is a personal profile readme for my class assignment .
Somayeh Sadeghizadeh

## WorldCupMatches

For this mini project I worked on world cup matches dataset, which includes matches during **1930 to 2014** held in different cities between different teams with some variables which I focouced on some of them mainly such as Home team goals, away team goals, audience and some other variable to be used was created for this report such as total goals. Here I put some main Visualization of my project in this file:


* Checking the distribution of *Total Goals* using the *hist()* function. We can see in the graphs that the data is skewed to the right.

![2](https://user-images.githubusercontent.com/70166302/99691907-b610ae80-2a57-11eb-9108-f726feacd8dd.png)



*	Attendance in Home Town : to show Drawing number of attendances in home team matches in different cities, attendance in cities like London and Mexico City and Los Angeles were more than other cities for, to be more specific I filtered number of audiences between 70,000 to 150,000 and used the function of facet_wrap to separate cities.

![5](https://user-images.githubusercontent.com/70166302/99691923-bad56280-2a57-11eb-99db-4b0a2359a4d3.png)


*	Attendance VS. Home Team Name (More than 50000 attendance): Another format for checking games with high number of audiences for hometown games filled with total goals, in Brazil and Mexico had most audiences in home town matches.
*	With mutate function winning team variable is created to check some more items:

![6](https://user-images.githubusercontent.com/70166302/99691929-bc068f80-2a57-11eb-947b-2b53e66ace3a.png)

*	Attendance of Winning Teams with the Location of Game: This plot shows relationship of attendance vs winning teams and the location of matches are colored disceretly,also Netherland match there were fewest attendance to watch the game.

![7](https://user-images.githubusercontent.com/70166302/99691933-bd37bc80-2a57-11eb-94d6-26bb08d2608d.png)


*	Attendance VS. Total Goals: To see more details, filtered number of audiences for more than 90000 people and checked it versus number of total goals with the label of city on the games.as it can be seen for 2 goals games there were the most attendances in Rio De Janiro, using the label of cities on the plot.

![8](https://user-images.githubusercontent.com/70166302/99691942-bf018000-2a57-11eb-84e9-fa07fa11ffef.png)


*	Attendance vs. Date: Plot shows relation of attendance versus the year the match was held, it is also colored by winning team, using the scale_colour_iwanthue() function and palette of hues which has lots of colors for qualitative variable. Italy in 1970 has the most audiences more than 100,000 people.


*	Away team goals vs. Home team goals in USA: to check one country situations specifically USA home team goals vs. away team goals was considered, there were 5 away team goals for Czechoslovakia and 1 home team goals for USA, also 3 goals for USA and 0 for Paraguay, this way we can check every country more specifically. For writing on the plot, used annotate function and geom_label_repel to have rectangle labels.


*	Total goals in USA matches over the years: To continue focusing on one specific country, using geom_point it can be seen than during the year’s total goals of a match to be more obvious I used facet wrap function to show the away team player. For instance, in play with Czechoslovakia there were total of 6 goals in 1990.



##Conclusion:
•	According to histograms of Attendance and Total Goals as we see skewness in both plot, so if we want to have more specicific result, it is better to normalize them at first then work on data.
•	Acoording to boxplot plots outliers for home team and away team goals are 7 and for total goals are 9 that should be considered in our analysis.
•	Teams of Brazil and Hungary had the most Total Goals in home town matches.
•	For audiences between 70,000 to 150,000 Number of attendance in cities like London and Mexico City and Los Angeles were the most in home town matches.
•	For More than 50,000 attendance Teams of Brazil and Mexico had most audiences in home town matches.
•	For audiences more than 90,000 for games with 2 goals there were the most attendances in Rio De Janiro.
•	Italy in 1970 has the most audiences more than 100,000 people.
•	specifically for USA home team goals vs. away team goals was considered, there were 5 away team goals for Czechoslovakia and 1 home team goals for USA, also 3 goals for USA and 0 for Paraguay.
•	In matches which Brazil had played as one side there were lots of goals.

