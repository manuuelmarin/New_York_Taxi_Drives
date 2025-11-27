# NewYorkTaxiDrives
The dataset contains the yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP). The trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.

You can find more information of the dataset in the following link: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

This repository hosts the Big Data analysis project commissioned for the NYC Taxi Trip Record dataset, executed using Apache Spark. The environment was containerized using Docker (with quay.io/jupyter/pyspark-notebook), ensuring a scalable and reproducible setup for handling large volumes of data.

The analysis includes three mandatory studies, covering taxi speed by hour, common trip routes based on location IDs, and a financial study focused on tipping behavior by passenger count. A core requirement of this project was demonstrating proficiency across the full Spark API, with one study leveraging RDDs, DataFrames, and direct SQL commands. Furthermore, the repository includes a comprehensive scalability and performance report analyzing the execution speed-up against increasing core counts, justifying the code's efficiency and parallelization capability.
