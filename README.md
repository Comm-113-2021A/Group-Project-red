# Group-Project

``` {r install}
library(tidyverse)
```


1) Question: Which position in the NBA is most likely to win an award (MVP, First-Team, Rookie of the Year)?
We will explore if there is a certain position in the NBA that is more likely to get an end of season award than others. Also, we will evaluate if this distribution has changed over the years as the NBA has changed. 

variables: position, type of award, player ID, year
cases: each NBA player who has won award since 1946
data from: Open Source Sports Website

2) (code in awards.Rmd)

1719 rows, 6 columns


3)
Response: frequency of MVP, NBA First-Team, and Rookie of Year among G,F and C
Explanatory: type of award

We made tentative graph but need to select certain awards and format it better. We also want to make a model that shows the year on x-axis and frequency on y with each point representing if a certain position earned an award in that year. 