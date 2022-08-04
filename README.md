# Count-finger
An Application that can detect a hand,segment the hand and count the number of fingers being held.  
Pre Requisite 
-> OpenCV 
-> Numpy 
-> Other Py Libraries 
-> Covex Hull  Project Flow 
-> Grab a ROI(Region of Intrest) 
-> Calculate a running average background value for 60 frames of video. 
-> Hand enters in ROI 
-> Thresholding is done 
-> CONVEX HULL to draw polygon around the hand.
