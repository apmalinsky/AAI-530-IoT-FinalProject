# Room Occupancy and Temperature Estimation
One application area within the Internet of Things (IoT) paradigm is energy consumption optimization. Within the context of buildings for example, large portions of energy are spent on heating, ventilation, air conditioning, and lighting systems. A method to tackle optimizing energy usage in these systems is to use real-time human occupancy data for demand-driven usage (Singh et al., 2018). Researchers Sing et al. conducted an experiment in which they set up an IoT system with multiple sensors within a room of a building and applied machine learning algorithms on the data collected to predict room occupancy count. In a real-world business use case, the predictions from these AI methods would be the driving force in the ultimate decisions being relayed to the energy producing systems. In this project, we perform [exploratory data analysis](https://github.com/apmalinsky/AAI-530-IoT-FinalProject/blob/main/notebooks/eda-data-clean.ipynb) on that experiment’s Room Occupancy Estimation dataset (Adarsh Pal Singh, 2018), and apply a deep learning method for [classifier prediction](https://github.com/apmalinsky/AAI-530-IoT-FinalProject/blob/main/notebooks/classifier-pred.ipynb) on room occupancy count as well as a method for [time series prediction](https://github.com/apmalinsky/AAI-530-IoT-FinalProject/blob/main/notebooks/classifier-pred.ipynb) on room temperature.

# IoT System Design
We designed a theoretical IoT system based on the chosen dataset. The design features sensors measuring temperature, light, sound, CO2, and digital passive infrared (PIR).

![alt text](https://github.com/apmalinsky/AAI-530-IoT-FinalProject/blob/main/IoTSystemDesignDiagram.jpg)

# Tableau Public Dashboard Visualization
To simulate our IoT system design with real-time visualizations, we built a Tableau Public [dashboard](https://public.tableau.com/app/profile/alejandro.marchini/viz/AAI-530-Grp8/Dashboard1).

![alt text](https://github.com/apmalinsky/AAI-530-IoT-FinalProject/blob/main/TableauDashboardVisual.png)

## References
* Adarsh Pal Singh, S. C. (2018). Room Occupancy Estimation [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5P605
* Singh, A. P., Jain, V., Chaudhari, S., Kraemer, F. A., Werner, S., & Garg, V. (2018). Machine Learning-Based Occupancy Estimation Using Multivariate Sensor Nodes. 2018 IEEE Globecom Workshops (GC Wkshps), 1–6. https://doi.org/10.1109/GLOCOMW.2018.8644432
