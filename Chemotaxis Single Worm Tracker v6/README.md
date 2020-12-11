# Chemotaxis_Tracker_v6
Hallem Lab Chemotaxis Tracking Codebase

Version repository for Single Worm Chemotaxis Tracking Matlab code used in
Chavez *et al* 2020.


## Function Description
Custom Matlab scripts used to analyze single worm chemotaxis tracking assays. 
Flexibly handles both odor tracking and CO2 tracking assays.

Will translate pixel-based x/y coordinates generated in Fiji into cm-based coordinates. 
Generates plots of worm tracks, and calculates several quantifications, 
including:
- average speed (cm/s)
- distance ratio
- pathlength (cm)
- final location relative to control zone (cm)
- final location relative to experimental zone (cm)
- time in control zone (s)
- time in experimental zone (s)

The top-level .m file is "CT_WormTracks_v6.m"
