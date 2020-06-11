# Fast-Segmentation-based-Object-Tracking-Model

Demo
------
This is a gif of segmentation and tracking result of our model.\
![image](https://github.com/XYunaaa/Fast-Segmentation-based-Object-Tracking-Model/blob/master/samples/result.gif). 

This is an example of 2D tracking result of our model.\
![image](https://github.com/XYunaaa/Fast-Segmentation-based-Object-Tracking-Model/blob/master/samples/tracklets/tracklets_0006.png)  
![image](https://github.com/XYunaaa/Fast-Segmentation-based-Object-Tracking-Model/blob/master/samples/tracklets/tracklets_0016.png).   

After segmentation,our model uses the tracking vectors in each frame for matching track IDs with the famous
Hungary algorithm. This is an example of ID matching based on the tracking vector from masks.  
![image](https://github.com/XYunaaa/Fast-Segmentation-based-Object-Tracking-Model/blob/master/samples/tracking%20vector/sample1.png). 

This is a matching distance matrix of inter-frame ID matching.\
![image](https://github.com/XYunaaa/Fast-Segmentation-based-Object-Tracking-Model/blob/master/samples/matching_matrix.png)
