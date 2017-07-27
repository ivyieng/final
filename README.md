# About this [Visualization](https://ivyieng.github.io/final/flights)
This visualization follows the **interactive slideshow** narrative visualization structure. The slideshow structural layout was constructed using [reveal.js](http://lab.hakim.se/reveal-js) editor and all the charts were written using D3.js embedded in the slides as iframes.

## Scenes
There are 5 main scenes in between the opening and ending scene. Each scene consists of a single chart and description.

## Annotations
**Tooltips** - The tooltips in all charts follow the same CSS template to support visual consistency.

**Bar chart annotations** - As there are multiple bar charts in this visualization, they follow the same template to sure the axis labels and average lines are displayed in a consistent manner. For the "Average Departure Delay" bar charts in Scene 2 and 4, the average line will be cleared when users switch to the other bar chart.

## Parameters
**Slide number** - The slide number is shown in the bottom center of each of the 5 main scenes. The previous and next slide numbers are shown in the bottom left and right respectively.

**Bar chart parameters** - The bar charts on Scene 2 and 4 contain 2 input parameters controlled by radiobuttons. User can select to see the figures of average departure delay or the total number of flights.

**Map filter parameters** - The map on Scene 5-1 shows all the US airports by default. The 3 parameters by levels of delay controlled by checkboxes can let users multiselect or deselect to filter the airports on the map.

## Triggers
**Slide navigation controls** - The navigation can be controlled by keyboard arrow keys or by pressing the "<" and ">" button in the bottom right corner of each slide.

**Tooltips** - The tooltips in all the charts are triggered by mouseover event on chart elements.

**Bar chart selection** - The 2 radio buttons on Scene 2 and 4 allow users to select and view two different set of figures in the bar chart.

**Map filter** - The 3 checkboxes on Scene 5-1 allow users to filter the airports by 3 levels of delay.

**Button and hyperlinks** - The button and hyperlinks in the opening and closing scenes

## User Interface Events
**Mouse click** - User interacts by clicking on buttons, hyperlinks, slide navigation controls, check boxes, radio buttons

**Mouse hover** - User triggers tooltips on chart elements by mouse over events


## Credits
Heatmap inspired by [Tom May's Block](http://bl.ocks.org/tjdecke/5558084), see [license](/license/heatmap-license.txt).

## Source
Data from [Bureau of Transport Statistics (BTS) - On-Time Performance dataset](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time)

## Author
Manieng Ivy Lao
[mlao2@illinois.edu](mlao2@illinois.edu)
