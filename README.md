# A machine learning framework for predicting agriculture terrace suitability using positive and unlabelled datasets: an application for the Troodos Mountains, Cyprus
_____

## Authors
#### Aman Kumar Meena<sup>1</sup>, Christos Zoumides<sup>1</sup>, Hakan Djuma<sup>1</sup>, Ioannis Sofokleous<sup>1</sup>, Corrado Camera<sup>2</sup> and Adriana Bruggeman<sup>1</sup>  
<sup>1</sup>Energy, Environment and Water Research Centre, The Cyprus Institute, Aglantzia, Lefkosia 2121, Cyprus  
<sup>2</sup>Dipartimento di Scienze della Terra “A. Desio”, Università degli Studi di Milano, Via Mangiagalli 34, 20133 Milan, Italy
______

## Abstract
Terraces are a defining feature of Mediterranean mountain landscapes, enabling agriculture on steep slopes while providing multiple ecosystem services. Land suitability analysis (LSA) can guide authorities and land users to sustainably manage and expand these environments. It typically requires fully labelled datasets, but in many real-world applications only a fraction of positive examples is available, with the rest unlabelled. This study aims to present an integrated predictive modelling framework that combines GIS with data-driven Machine Learning (ML) techniques, capable of learning from positive and unlabelled datasets for LSA. The proposed framework was applied to develop a terrace suitability map for Cyprus’ Troodos Mountain. A 5-m DEM was processed to extract the mountain area, with elevation ≥500m and slopes ≥15%, defining the study area. Crop plots registered under the Single Area Payment Scheme of the European Common Agricultural Policy were used to classify the study area into Terrace-Present (TP) and Terrace-Absent (TA) cells, with TP serving as labelled positive and TA as unlabelled samples. A two-step ML approach was applied, first identifying reliable negatives from TA cells, then using these with TP cells for suitability prediction. Feature importance analysis identified land cover, terrain slope and tree cover density as the most influential parameters for terrace suitability. Comparative analysis between 2017 and 2024 revealed abandonment of terraced agricultural land (29% decrease) as well as revitalization (12% increase). The resulting suitability map and accompanying data layers are accessible through a Google Earth Engine application, aiming to support informed decision-making for sustainable landscape planning.

This research was supported by the REACT4MED Project (GA 2122), which is funded by PRIMA, the Partnership for Research and Innovation in the Mediterranean Area, a Programme supported by Horizon 2020, the European Union’s Framework Programme for Research and Innovation.
______

## Study Area
Contains raw and processed geospatial datasets.

## Scripts
Python scripts for analysis and modeling.

## Results
Final suitability maps and outputs.
