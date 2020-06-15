# Motion Detector
#### A desktop camera application that records movement times

***
*Thus project was created in an ongoing effort to learn, and become proficent in pything.  This application makes use of the Open-CV library for image manipulation, the pandas library for data collection, and the bokeh library to display the output in an easy to understand chart.* 
***

This application will access the camera on any laptop, and detect any motion within the frame.  The motion will be highlighted with a green square outline as it is occurring.  Once the user presses 'q' to quit the program a CSV file will be created with the start and stop times of detected motion.  Additionally, an HTML file will automatically be created and open with a chart displaying when motion was detected.  

* Begin by double clicking the executable file "Motion Detector.exe".  The image of your webcam's vew will appear.
<img src="/Screen Shots/1 - Open.PNG" />

* Once the application detects any motion, a green rectangle will appear highlighting it.  

<img src="/Screen Shots/2 - Motion.PNG" />

* At any time the user can press 'q' on the keyboard to quit.  Next and HTML file will automatically generate and open displaying when motion was detected in the video.  

<img src="/Screen Shots/3 - Output.PNG" />