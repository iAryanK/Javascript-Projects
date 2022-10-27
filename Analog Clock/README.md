
# Analog Clock using PURE JS

This is a beginner's project where an analog clock is designed while applying the concept of HTML, CSS and pure Javascript.

## Overview of index.HTML

A main division named 'clockContainer' contains three sub-divisions.
- hour
- minute
- second

## Overview of index.CSS

Every division of index.html is given some width and height and necessary design to make a better view of hands of the analog clock.

* NOTE: The 'clockContainer' is made 'position: relative;' so that all the hands of the clock are fixed at their position, that adds to the responsiveness of the design.

## Overview of index.JS

### for hour hand

12 hours = 360 degree

1 hour = 30

h hours = 30h

To add additional rotation in hour hand with respect to minute hand, 

60 minutes = 30 degree

1 minute = 1/2

m minutes = m/2 

- h hour = 30h + m/2


### for  minute hand

60 minute = 360 degree

1 minute = 6 

- m minutes = 6m

### for second hand

6o second = 6 degree

1 second = 1/10

- s second = s/10



