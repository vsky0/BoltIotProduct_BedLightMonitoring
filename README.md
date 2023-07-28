# BoltIotProduct is Bed Light on or off.
In this repository we will find the different products which involves the IoT based products collecting data, representing data on graphs and predictng.

Simply basic IoT products which are created using the Bolt IoT.

This product aims to find out whether the bed light is on or off.

Steps:

Step 1 : Fetch the latest sensor value from the Bolt device.

Step 2 : Store the sensor value in a list, that will be used for computing z-score.

Step 3 : Compute the z-score and upper and lower threshold bounds for normal and anomalous readings.

Step 4 : Check if the sensor reading is within the range for normal readings.

Step 5 : If it is not in range, send the SMS.

Step 6 : Wait for 10 seconds.

Step 7 : Repeat from step 1.

Note:

The math and statistics libraries will be required for calculating the Z-score and the threshold boundaries.

we calculate the Z score (Zn) for the data and use it to calculate the upper and lower threshold bounds required to check if a new data point is normal or anomalous.
