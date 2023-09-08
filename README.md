# Data-Visualization-with-R
In this case study I will load, tidy (clean) and view palmerpenguins data in R Studio. I will also wrangle data to have a clear concept of some of the common functions in R. I will then jump onto visualisation and some model training codes.

Installing the palmerpenguins data set![image](https://github.com/benislam/Data-Visualization-with-R/assets/43390687/2c384c3b-dc95-48e8-b118-7535c10ba294)

install.packages("palmerpenguins")

Load the Data:

data(penguins, package="palmerpenguins")
library(palmerpenguins)
data("penguins")


Load packages:

library(car)
library(ggbiplot)
library(GGally)

library(car)
library(heplots)
library(candisc)


library(palmerpenguins)
library(corrr)
library(GGally)
library(recipes)
library(tidytext)
library(dplyr)
library(tidyr)
library(ggplot2)
theme_set(theme_minimal())

library(palmerpenguins)
library(dplyr)
library(ggplot2)
theme_set(theme_minimal())
library(palmerpenguins) # for data
library(dplyr) # for data-handling
library(corrplot) # for correlation plot
library(GGally) # for parallel coordinate plot
library(e1071) # for svm
data(penguins) # load pre-processed penguins 

From <https://www.r-bloggers.com/2020/07/basic-data-analysis-with-palmerpenguins/> ![image](https://github.com/benislam/Data-Visualization-with-R/assets/43390687/68bd8299-f7f3-417b-a80f-a83ef7187cf3)
