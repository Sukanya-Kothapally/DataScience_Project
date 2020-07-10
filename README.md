# Project Objective 

* To analyse changes in traffic congestion during game day vs non-game day in 2018-2019 NBA League that happened in moda center (portland).
* To analyse how the traffic is affected in nearby locations to moda center (Blazers play matches here) vs distant locations.

# Project Approach
 The idea is to collect the data of 5 nearby locations and 1 far location to the moda center on a game day and non-game day using data available on the portal. The data is collected using sensors placed at different mileposts on the highways. We assume that there exists congestion when the average speed of all vehicles passing through a milepost is less and therefore the project uses average speed to define congestion at different mileposts on the highway.

After collecting the required data, data cleaning is executed if necessary. Data is then loaded and processed in PostgreSQL. Data is analysed over different metrics and visualized using Tableau.

# Team Structure
We are a team of two Sowmya and Sukanya. We are planning to work together throughout the project and learn from each other. However, we have split up the responsibilities.
* Sowmya: Collecting data, Data analysis and cleaning.
* Sukanya: Processing and Visualizing the patterns in traffic congestion.

# Project Milestones
* Gather 2018-2019 NBA Schedule dates in moda center, in order to collect the data according to the dates.
* Collect traffic data of six locations (5 near and 1 far) from the portal.
* Convert the  generic collected data, clean and clear the data by removing unwanted rows like speed = 0 or speed = negative number or if volume = 0 when speed > 0.
* Creation of tables in the database based on the game and non-game days.
* Processing the data to perform analysis.
* Make a list of all the different analyses that we wanted to do in this project.
