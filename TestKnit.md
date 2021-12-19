Untitled
================

# Setting up my enviroment

Notes: setting up my R enviroment by loading the ‘tidyverse’ and ‘palmer
penguins’ packages

``` r
library("ggplot2")
library('palmerpenguins')
```

## Visualizations

Here we will go through a series of visualizations

### Flipper and Body mass in purple

Here, we plot flipper length against body mass

``` r
ggplot(data=penguins,aes(x=flipper_length_mm,y=body_mass_g))+
  geom_point(color="purple")
```

    ## Warning: Removed 2 rows containing missing values (geom_point).

![](TestKnit_files/figure-gfm/visualize%20flipper%20andd%20body%20mass%20in%20purple-1.png)<!-- -->
![visualize flipper andd body mass in purple-1](https://user-images.githubusercontent.com/70235515/146668675-3c5248c3-62b6-4629-978b-8211a0d71127.png)
