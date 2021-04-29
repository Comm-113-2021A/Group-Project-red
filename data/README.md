# data



```{r load-data1}
library(readr)
mvps <- read_csv("presentation_files/historical-mvps.csv")
view(mvps)

```

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

## name of data file

- `Rank`: goes from 1-10 in each reason on the players that receive the most MVP votes 

-`Player`: name of player

-`Age`: age of player when voting occurred

-`Tm`: current NBA team player is on

-`Pts Won`: amount of points received in MVP voting race

-`Pts Max`: maximum points a player could have received

-`Share`: percent of pts they won

-`G`: games played

- `Team Wins`: amount of wins the team the player is playing with wins that season

-`Overall Seed`: the ranking of team in NBA based of record

-`MP`: minutes played per game

- `PTS`: average points per game in that season they are voted on in MVP

-`TRB`: total rebounds per game

-`AST`: total assists per game

-`STL`: total steals per game

-`BLK`: total blocks per game

-`FG%`: field goal percentage

-`3P%`: three point percentage

-`FT%`: free throw percentage

- `WS`: win shares, a measure that is assigned to players based on their offense, defense, and playing time

- `WS/48`: win share per 48 minutes

-`VORP`: value over replacement

