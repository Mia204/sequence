#load the necessary libraries
```{r}
#a package for reading in data
library(readr)
#a package for reading data manipulation
library(dplyr)
#a package for plotting your data
library(ggplot2)
#specify this to enable plotting to work
options(bitmapType='cairo')
```

#import the example compensation data
```{r}
Comp<- read_csv("compensation.csv")
```
