# activity-tracker
Data exploration and processing of activity tracker data; users clustering and users analysis.

Data Exploration:
* [Users](http://htmlpreview.github.io/?https://github.com/renatalucia/activity-tracker/blob/master/data_exploration/users_filter.html): Visualize statistical profile of user data, filter noisy data.

* [Weights](http://htmlpreview.github.io/?https://github.com/renatalucia/activity-tracker/blob/master/data_exploration/weights_filter.html): Visualize statistical profile of weight data, filter noisy data, filter by metric (kilos), handle multiple measure at the same timestamp, compute bmi.

* [Activities](http://htmlpreview.github.io/?https://github.com/renatalucia/activity-tracker/blob/master/data_exploration/tracker_filter.html): Visualize statistical profile of activity data, filter noisy steps counts based on threshold, steps _vs_ distance ratio, and steps _vs_ calories ratio.

* [Bmi, Steps correlation](http://htmlpreview.github.io/?https://github.com/renatalucia/activity-tracker/blob/master/data_exploration/bmi_steps_correlation.html): Visualize correlation between bmi and number of steps considering all users, and inidividual users.



Clustring and Retrieval:
* [Scripts](http://htmlpreview.github.io/?https://github.com/renatalucia/activity-tracker/blob/master/clustering/users_clusters_visualize.html): Python scripts to compute users clusters based on bmi, age and activity level; and to perform cluster based analysis for a given user (find best cluster, show individual results compared to similar users, show example of bmi _vs_ steps evolution inside the cluster).

* Samples: Sample reports for two different user data.
	* [User1](https://github.com/renatalucia/activity-tracker/blob/master/clustering/report_1.pdf): New user data (not used in the clustering process).
	* [User2](https://github.com/renatalucia/activity-tracker/blob/master/clustering/report_2.pdf): User data used in the clustering process. 
