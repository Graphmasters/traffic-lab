# traffic-lab

This repository contains movement data of cars recorded with mobile phones during traffic experiments.

## Verkehrsexperiment May 2022

The traffic experiment conducted on May 10th, 2022 at 16:40 CEST showed the influence of route choice on the 
total travel time of a fleet of vehicles during the rush hour in Hanover, Germany. 
Circa 40 vehicles were driving from the same start location to a common destination. 
The vehicles were starting consecutively from a parking lot.
Every second vehicle was following the route guidance of Google Maps and every other vehicle was using NUNAV Navigation.

### Results

The recorded data is in the [route-choice](route-choice) directory. 
The trajectories of both groups can be viewed on a map:
- [Google Maps](route-choice/trajectory-geojson_route-choice_GoogleMaps.json)
- [NUNAV Navigation](route-choice/trajectory-geojson_route-choice_NunavSwarm.json)

The travel times of both fleets are compared in a Jupyter Notebook: [Evaluation](route-choice/evaluation-simple.ipynb).  
