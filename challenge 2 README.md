# Kickstarter-analysis

## Overview of Project

### Purpose

 * The Purpose of this analysis was to refractor the code to see if the code would compile the data faster than the original VBA code. this would tell us if the code is more efficient then the original.  



### Results
* We can see that the results for the returns are essentially the same with the module code and the refractor code. however with the refractor code we have a much faster compilation time. this can be seen with the images from the refractor code i have written. this helps in times when dealing with large sums of data, for there to be code that will run quicker.  

![./Resources/VBA_CHALLENGE_2017.png]
![./Resources/VBA_CHALLENGE_2018.png]

* differences in the refractor code was to create a tickerIndex to replace the nested for loop in the module vba code. this reduced the vba run time in turn
![./Resources/CODING.png]

* We can see from the data, we can see that the  year 2017 was a year that had much better returns than in 2018. as the code estimated the returns by calculating the ending price of the ticker and starting price of the same ticker, this showed that 2017 was a more profitable year for the stocks chosen. 

![./Resources/2017 Return.png]
![./Resources/2018 Return.png]


### Summary
*  	The advantages to refactoring code is to get the code to run more smoothly and faster, which is important when dealing with large amounts of data.
	however the disadvantages are that you may get it to run slower, or in the attempt to refractor the code, you find code that doesnt work properly, there are many iterations that can be done with code in order to create the desired outcome. a faster compiler to the data wins out in the end. 

	
	
