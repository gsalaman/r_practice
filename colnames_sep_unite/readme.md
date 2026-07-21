# day 1 practice excercises

We're going to be operating on the "fynn.csv" file.  
Make a new file called `day1.r`

Start by including the following libraries:
```
library(csv)
library(tityverse)
```

We're then going to import the fynn.csv file into R as the cards array:
```
cards <- read_csv("fynn.csv)
```

Check out the created array.  Everything is in one column...called "Glenn's Commander Deck".

## Excercise #1: colnames 
Use the colnames function to change the name of our column to something else.  If you need an example, check out glenn_part1.R

## Excercise #2: using separate to split the data
First, some syntax.  
separate takes a vector and column and splits that column into MULTIPLE columns, based on a saperator.  
remove = FALSE means DON'T remove the original column...by default, it will (same as remove=TRUE)
