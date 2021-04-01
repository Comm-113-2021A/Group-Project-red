Project title
================
by Team name

<<<<<<< HEAD
## Summary

Write-up of your project and findings go here. Think of this as the text
of your presentation. The length should be roughly 5 minutes when read
out loud. Although pacing varies, a 5-minute speech is roughly 750
words. To use the word count addin, select the text you want to count
the words of (probably this is the Summary section of this document, go
to Addins, and select the `Word count` addin). This addin counts words
using two different algorithms, but the results should be similar and as
long as you’re in the ballpark of 750 words, you’re good! The addin will
ignore code chunks and only count the words in prose.

You can also load your data here and present any analysis results /
plots, but I strongly urge you to keep that to a minimum (maybe only the
most important graphic, if you have one you can choose). And make sure
to hide your code with `echo = FALSE` unless the point you are trying to
make is about the code itself. Your results with proper output and
graphics go in your presentation, this space is for a brief summary of
your project.

## Presentation

Our presentation can be found [here](presentation/presentation.html).

## Data

Include a citation for your data here. See
<http://libraryguides.vu.edu.au/c.php?g=386501&p=4347840> for guidance
on proper citation for datasets. If you got your data off the web, make
sure to note the retrieval date.

## References

List any references here. You should, at a minimum, list your data
source.
=======
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
>>>>>>> d11d109627a59b8c03ec982ef5e6b7997b14c5cf
