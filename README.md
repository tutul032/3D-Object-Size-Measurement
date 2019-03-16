# Machine vision based detection and size measurement of objects on a conveyor belt:
3D reconstruction required at least two camera views. In this project single camera has been used and the three frame differences has been used to get the second view of the camera. Then background subtraction applied to the interested objects. Finally triangulation method applied with help of feature detection method to get the 3D point cloud. 
1. 3D point cloud obtained via triangulation
![image](https://github.com/tutul032/3D-Object-Size-Measurement/blob/master/3D%20Object%20View.jpg)
2. Background subtraction applied on interested objectets
![image](https://github.com/tutul032/3D-Object-Size-Measurement/blob/master/Background%20Subtraction.jpg)
3. Feature detection on subtracted objects 
![image](https://github.com/tutul032/3D-Object-Size-Measurement/blob/master/Feature%20Detection.jpg)
4. Cuboid drawn on the 3D point cloud of each object to measure the dimention by subtracting the cuboid coordinates
![image](https://github.com/tutul032/3D-Object-Size-Measurement/blob/master/Object%20Measurement.jpg)
