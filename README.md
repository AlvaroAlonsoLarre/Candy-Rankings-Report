# HALLOWEEN CANDY RANKINGS PROJECT

![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![EXCEL](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

![Report](https://github.com/AlvaroAlonsoLarre/Candy-Rankings-Report/blob/main/IntroProjectMavenHalloween.jpg)

📊 **[Link to the Report](https://app.powerbi.com/view?r=eyJrIjoiMWFlOTNlOWUtMjhlMC00NzE3LTkzNWItYWFiMjE3N2UwYmEwIiwidCI6ImI3MzdhZDYyLWRiZTEtNGUzMi05OTE0LWEyMDNhNTRkMjQzZSJ9)**

## Foreword
Survey research was conducted to discover which is the most popular candy for Halloween.  Using online votes, 85 types of candy were matched up 269.000 times to create a ranking.
Basing on that ranking and the features of the 85 different candies, I analysed and decided which are the 3 most successful sweets and developed a report with the conclusions.

## Dataset
The dataset consists of one csv files with the information of the 85 types of candy. This info has 5 different presence/absence of ingredients, 4 features and 3 percentage rankings (sugar and price and the matchup win) per candy. 

## Data Process and Analysis
The first step of this phase was grouping the win percenage by the 5 different ingredients and the 4 features to calculate the average of success. So that, I got the comparison between the candies with chocolate vs without chocolate, with caramel vs without caramel, bar shape candies vs no-bar shape candies…

After that, I calculated the correlation coefficient between sugar percent and win percent and between price percent and win percent.

Finally, I calculated a new ranking that considerers all the ingredients, the features, success percent, sugar contents percent, price percent and their two correlation coefficients. I called this value “Balance” ranking and I used the following formula:

Balance = Success (%) - (Sugar (%) * SugarSuccess Corr. Ceof. * 100) - (Price (%) * PriceSuccess Corr. Ceof. * 100) + (Dif. Avg. Success by Ingredients and Features*)
 
![Table](https://github.com/AlvaroAlonsoLarre/Candy-Rankings-Report/blob/main/TableMavenHalloween.png)


## Summary
Using the analysis, it is easier to see which component and feature is more valued by audience. 

Nuts, chocolate, nougat or caramel are more successful, but fruits are not as appreciated as the other ingredients.

Online votes showed that candies with crisped rice, wafers or a cookie component are more successful, and they prefer soft than hard candies. 

Furthermore, No-Pluribus and bar shape candies were more successful on the online votes ranking.

Lastly, the data analysis revealed that there is a weak direct correlation between Sugar and Success or Prices and Success. 

The report sums up 4 different top 3 rankings:
- Success Ranking: The top overall win percentage (Reese's Peanut Butter cup, Reese's Miniatures,Twix)
- Sugar Ranking: The top less percent of sugar(One dime, One quarter, Reese's Miniatures)
- Prices Ranking: The top cheapest candies (Tootsie Roll Midgies, Pixie Sticks, Fruit Chews)
- Balance Ranking: The top successful candies considering the features, sugar and price (Snickers, Reese's Miniatures, Kit Kat)
