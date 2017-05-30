# RFSensor (V. 0.0.0) 
This is a small executable that uses the MLX90614 IR Sensor along with a Raspberry pi 3 and the bcm2835 library to log tempuratures in a csv file

NOTE: This program must be run with Root Privileges.

Issues:
-AMBIENT and OBJECT tempuratures must be changed in the code itself. I might add command line functionality later.
-Time always logs every one minute. I might add an option to change this later.
-The progam has no way of quitting without stopping the process and closing the terminal.
