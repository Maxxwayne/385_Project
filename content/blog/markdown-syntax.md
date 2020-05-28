---
aliases:
- migrate-from-jekyl
author: Maxx Wayne
date: "03-09-2020"
title: What I have learned from STAT 385
type: post
---
Throughout the first half of this semester, I have learned how to use built in R functions and write my own. Here is an example:

```{r}
combo=c(2,4,18)
random=sample(combo,2,replace=TRUE)
random

game=function(goals_for,goals_against){
  if(goals_for>goals_against){
    outcome='win'
  }
  if (goals_for=goals_against){
    outcome='tie'
  }else{outcome='lose'}
  outcome
}
game(6,3)
```

Unless I set a seed, this 'random' will be different almost everytime because it is a random sample. I also created a simple function 'game,' which can tell you if you win or lose a soccer game based on the amount of goals your team scored and allowed.

I can also make plots and charts:

```{r}
hist(iris$Sepal.Length,breaks=5)
plot(iris$Petal.Length,iris$Sepal.Length)
```

I have also learned how to make for loops, but they are technically not the most efficient way of running data on RStudio. I have gained a lot of knowledge about RStudio, R Markdown, GitHub, and coding in general throughout the first half of this semester. I am looking forward to furthering my coding career.

