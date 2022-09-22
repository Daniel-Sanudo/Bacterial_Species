# Bacterial_Species

This repository contains a visualization of a given dataset about bacterial biodiversity found in the belly button of different test subjects. The visualization is done using html, css and bootstrap element and the logic behind the graphs and panel information is done with js and d3. The link to the github pages is [here](https://daniel-sanudo.github.io/Bacterial_Species/)

## Overview

![index](/images/Github_page_landing.png)

The visualization dashboard consists of a Test ID No drop down menu selection, a panel with the demographic information of the chosen Test Subject ID and 3 different graphs.

### Horizontal Bar Chart

This graph shows the 10 bacterias with the highest sample value for each Test Subject, these are sorted descendingly with the Y-axis labels showing the bacteria label and the X-axis the amount of samples found. Hovering above each data entry shows the bacteria labels that correspond to each OTU ID.

### Gauge chart

This visual aid allows a faster visualization of how many times did the Test Subject wash their belly button. The black graph corresponds to the Test Subject's WFreq entry (weekly frequency, this can also be seen in the Demographic Info panel).

### Bubble Chart

This bubble plot gives a more complete overview of the Test Subject bacteria samples, unlike the horizontal bar chart, all the bacteria samples are included here.

The size of the bubbles corresponds to the sample value of each OTU ID, thus the bigger the bubble, the higher the sample value. Hovering over each bubble shows two pieces of information. The first one is inside a parenthesis with the following format (x, y) where x is the OTU ID and y is the sample value. The next line contains the bacterial sample label.

## Customization

~~~~
.jumbotron {
  background-image: url("https://www.mcgill.ca/newsroom/files/newsroom/channels/image/human-microbiome.jpg");
  background-size: cover;
  color: #FFFFFF;
}

body {
  background-color: #8adfe3;
  font-family: 'Courier New', monospace;
}
~~~~

These css formats found inside the index.html accomplish the following:
1. Add a background image to the jumbotron.
2. Change the jumbotron's font color.
3. Change the body's background color.
4. Change the body's font.