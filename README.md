# CANeo-self-driving-car
i  made 4 ECUs to simulate our project (Max no of ECUs for Demo version is 4 ): 1)main ECU : to control the function of the other 3 ECUs
2)control ECU:to show the speed , the steering angle of the car,flag to show autonomous or manual control 
and flag to show if the driver is distracted
3)steering_det : takes the steering angle and driver status and send it to the control ECU
4)detection ECU : takes the data of 3 cars in front of the cars one in middle and the others left and right
and takes the distance status of the three cars (far near critical) and send these data to control ECU
