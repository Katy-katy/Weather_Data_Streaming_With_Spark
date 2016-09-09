# Analyzing Weather Sensor Data with Spark Streaming

This project was created as an assignment for “Big Data Integration and Processing” class by University of California, San Diego (https://www.coursera.org/learn/big-data-integration-processing/home/welcome).

The goal is to calculate the max and min wind direction in degrees as data is coming.

I use 10 seconds "window" with shift in 5 second (the second part of each window becomes the first part of the next window).

The program creates streaming context, reads streaming data, parses each line of the data using a regular expression, and then calculates max and min wind direction for each window. 
