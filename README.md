# Road-Traffic-Analysis
This project aims to analyze Hong Kong Road Traffic in 2024.
## Background
Driving the objective of identifying the data and having a better understanding of the traffic in this city.\
The source file represents specific monitoring points in different districts in Hong Kong, providing details such as road name, easting, northing, latitude, longitude and rotation value.\
In Hong Kong, several detectors and cameras monitor the road at different points.\
![image](https://github.com/user-attachments/assets/6ce7dd77-f5dc-4114-978e-5790542a3190)\
The color represents the number of traffic monitoring points, more dark means more monitoring points, more light means fewer monitoring points. \
![image](https://github.com/user-attachments/assets/88bdeba5-cc90-4261-9e1e-063a27110b26)\
Yuen Long had the darkest color, which has 131 monitoring points.\
![image](https://github.com/user-attachments/assets/e60c81d1-1124-4ceb-aeb7-77cbf4e71625)\
Sha Tin had the 2nd darkest color, which has 101 monitoring points.\
![image](https://github.com/user-attachments/assets/889ab0a0-deaa-460e-9558-866c226743b3)\
Tsuen Wan had the 3rd darkest color, which has 90 monitoring points.\
## Tasks
Five main tasks are the goal of this project:
1.  Linear Regression: Given the lane volume, lane occupancy, visibility,  humidity and wind speed data, predict the lane speed at the same ten-minute period.
2.  Support Vector Machines (SVM): Given the lane speed, lane occupancy, visibility, humidity and wind speed data, classify the lane volume at the same ten-minute period.
3.  K-Nearest Neighbors Regression: Given the lane volume and lane speed, classify the lane occupancy at the same ten-minute period.
4.  K-Means: Segment the roads into clusters based on traffic volume and time of day.
5.  K-Means: Segment the accident statistics into clusters based on rainfall and traffic accidents.
## Limitation
-  Some short-term weather data are repetitive and do not change much. It will be difficult to predict.
-  The data is relatively scattered and has no obvious characteristics, making it difficult to classify and cluster by building a model.
-   Real-world data is complex and messy, making the algorithm difficult to process.
**For the result, please check the Tasks file**

