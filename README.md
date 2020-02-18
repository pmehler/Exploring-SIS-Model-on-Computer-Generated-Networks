# Exploring-SIS-Model-on-Computer-Generated-Networks

Inspiration taken from Romualdo Pastor-Satorras and Alessandro Vespignani, Epidemic dynamics and endemic states in complex networks (2001)

This project is a fun exploration into how infections interact in different environments.  I look specifically at the differences between random and scale free graphs in this project. 

## Summary of concepts encountered:

The epidemic threshold is the ratio between the probability a node is cured divided by the average degree.
The spreading rate is the ratio between the infection probability and cure probability.
When the spreading rate exceeds the epidemic threshold, the infection persists, if not, it dies.
Special Case:  Inhomogeneous (eg. Scale Free) graphs with y < 3 have an epidemic threshold of 0!  The infection always persists!

## Spread of Infection:

Two starting Options:
- Single infected Node; Low Density Directed Graphs will most often remain partially healthy, even without cure
- Half of nodes begin infected; Infection percentage often converges
