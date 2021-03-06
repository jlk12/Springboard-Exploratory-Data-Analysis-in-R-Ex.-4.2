# Springboard-Exploratory-Data-Analysis-in-R-Ex.-4.1
1 - Have a look at the str() of the titanic dataset.  

2 - Plot the distribution of sexes within the classes of the ship.
  Use ggplot() with the data layer set to titanic.
  Map Pclass onto the x axis, Sex onto fill and draw a dodged bar plot using geom_bar(), i.e. set the geom position to "dodge".

3 - These bar plots won't help you estimate your chances of survival. Copy the previous bar plot, but this time add a facet_grid() layer: . ~ Survived.

4 - We've defined a position object.

5 - Include Age, the final variable.
  Take plot 3 and add a mapping of Age onto the y aesthetic.
  Change geom_bar() to geom_point() and set its attributes size = 3, alpha = 0.5 and position = posn.jd.
  Make sure that Sex is mapped onto color instead of fill to correctly color the scatter plots.

# Springboard-Exploratory-Data-Analysis-in-R-Ex.-4.2

Calling mosaicGG(adult, "SRAGE_P","RBMI") will result in the plot you've been working on so far. Try this out. This gives you a mosaic plot where BMI is described by age.

Test out another combination of variables in the adult data frame: Poverty (POVLL) described by Age (SRAGE_P).

Try the function on other datasets we've worked with throughout this course:

mtcars dataset: am described by cyl

Vocab dataset: vocabulary described by education.
