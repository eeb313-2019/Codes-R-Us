# Possible analyses

1) Do more diverse communities have more complex trophic interactions?

Simpson's diversity index can be used to determine diversity for each geographic location. To organize our data, we will need to create a table with columns: species, abundance, and geographic location. Food webs will be created from the R package "food-web". Complexity of the food web will be equal to the number of interactions.

2) Is the ratio between predator and prey mass (and their variation) constant through life stages?

To organize our data, we will create a table with columns: life stage, predator species and their mass, and prey species and their mass. A possible analysis that could be used is ANOVA between predator/prey mass for adults and juveniles.

3) Does animal size (mass and length) change with latitude?

To organize our data, we will create a table with columns: latitude, species, and mass of species. An additional table will be made with the same columns, but with species length instead of mass. We will add columns to these tables for the random effects tested. We will use a linear model, where fixed effects will be mass, random effects include depth, predator/prey, and feeding type.

4) How do total abundance and species abundance change with depth?

To organize our data, we will create a table with columns: depth, species, and abundance of each species. We will use a linear model. Fixed effects will be abundance, random effects include latitude, predator/prey, and feeding type.

# Possible results tables

1) Do more diverse communities have more complex trophic interactions?

A column for diversity index, and a column for number of connections in food web (trophic diversity). Each row will represent a different location.

2) Is the ratio between predator and prey mass (and their variation) constant through life stages?

The output table of the ANOVA, including relationship and strength.

3) Does animal size (mass and length) change with latitude?

We will make a table of a variety of models using various random effects, and compare AIC values.

4) How do total abundance and species abundance change with depth?

We will make a table of a variety of models using various random effects, and compare AIC values.

# Possible results figures

1) Do more diverse communities have more complex trophic interactions?

Scatterplot of diversity index vs number of connections. We will also have a world map indicating the different geogrpahic locations. The food web will also be included to show trophic interactions. 

2) Is the ratio between predator and prey mass (and their variation) constant through life stages?

Scatterplot of prey mass vs predator mass colored by feeding type. Variation could be represented with a boxplot. We may log transform size values if the variation makes the pattern unclear.

3) Does animal size (mass and length) change with latitude?

Scatterplot of mass vs latitude (or length vs latitude) with a line of best fit based on regression (see lecture 8, page 5).

4) How do total abundance and species abundance change with depth?

Scatterplot of abundance vs depth with a line of best fit based on regression.
