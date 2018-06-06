## The Impact of Student-Faculty Interaction on Students’ Retention in Undergraduate Communities

The educational institution must overcome various obstacles to produce the best teaching
and better talents to the nation, one of the prominent and most widely observed crises in every
educational institution is student dropouts. Student dropouts are not something which is
identified in recent year, student dropouts and early leavers are one among the major problem
every institution experience since the educational institutions were established. Student dropouts
at undergraduate universities is a problem that affects students, faculties, administration and the
institution. Therefore, the main purpose of this research is to understand what measures Universities can take to retain their students and increase retention.

## Code

```{r}
library(readxl)
```

```{r}
Project_Data <- read_excel("C:/Users/Gayathri Vinoth/Desktop/ANLY-699-Project/Data/ANLY-699-Project-Data.xlsx")
```

```{r}
hist(Project_Data$Q13b, 
     main="Histogram for Quality of Student-Faculty Interaction", 
     xlab="Student-Faculty")

hist(Project_Data$Q14b, 
     main="Histogram for Univeristy Support to help students succeed academically", 
     xlab="Student support")
```


