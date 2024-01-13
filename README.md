# End-to-End (E2E) and V2X Delays Analysis<br> 
__subcriber_delay__ - This is a Python script developed for analyzing and logging V2X (Vehicle-to-Everything) and E2E (End-to-End) communication delays in a ROS environment. The script subscribes to relevant ROS topics, extracts essential data, and calculates delays, providing valuable insights into the performance of communication systems.<br>
<br>
__post_processing__ - This file is a Python script designed for analyzing and visualizing delay data from a CSV file. Leveraging popular libraries such as Pandas, Matplotlib, NumPy, and SciPy, this tool provides insightful statistics and graphical representations related to communication delays in a given dataset.<br>
<br>
__Probability_Density_Function__ - Below graph represents probability density function between delay of V2X (Vehicle-to-everything) & E2E (End-to-End) message.The upper graph shows the probability of a V2X message having a delay of a certain amount of time. The peak of the PDF is at around 100 ms, which means that most V2X messages have a delay of less than 100 ms. However, there is a tail to the PDF that extends out to 1400 ms, which means that some V2X messages can have delays of up to 1400 ms. While the lower graph shows measure of the time it takes for a message to be sent from one E2E device to another. The peak of the PDF(probability density function) for E2E delay is at around 200 ms, which is significantly lower than the peak for V2X delay. <br>
![Probability_Density_Function](https://github.com/aayushmistry/Car2X-/assets/155494744/ad6fde27-3dad-40e0-8a11-426c9c994d99)<br>
<br>
__Distance_vs_Delay__ - Below scatter plot represents the relationship between V2X delay & E2E delay vs. distance in milliseconds.The upper scatter plot shows V2x message delay vs. distance.The maximum delay for V2X messages is approximately 1400 milliseconds. While the lower scatter plot represents E2E delay vs. distance.The maximum delay for E2E delay is approximately 2500 milliseconds<br>
![Distance_vs_Delay](https://github.com/aayushmistry/Car2X-/assets/155494744/7885f172-4a35-474a-a089-f20a99158924)<br>
<br>
__Avg.Distance_vs_Delay__ - Below bar graph represents the relationship between V2X delay & E2E delay vs. distance at interval of 50 meters.The upper graph represents average delay for V2X delay vs. distance.It can be observed that maximum delay is seen between the interval of 900-950 meters.The lower grapgh represents average delay for E2E delay vs. distance.It can be observed that the delay of approximately 800 milliseconds is contant throughout the range of distance.<br>
![Avg Distance_vs_Delay](https://github.com/aayushmistry/Car2X-/assets/155494744/16689e5b-7517-4709-bc26-c4f00b2ece32)


 
