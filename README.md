# Interesting-stats-functions
#this is a brief summary of my thesis and some of the functions we made and use.

These were the functions that I used in my honours thesis "An Environmental problem in Spatial Statistics"

The aim of the experiment was to investigate the importance of space filling designs, by comparing the Mean Square prediction error achieved from performing kriging in 2 
space filling designs(Minimax and maximin) to a random design.

We used the exchange algorithm to perform maximin, and we used a package "fields" (cover.design function) to perform minimax.

An extention to our thesis was to assume that the nmomitors for simulating points were from 3 different companies and we had to acount for this effect, thus to find the
best design for each space filling design, we considered checking all available designs if the design set is not big, or an adjusted algorithm that uses cover designs for large design sets.
