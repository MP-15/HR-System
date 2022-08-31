# Human Activity Recognition using Smartwatch data analysis
Under this project student can recognize the human activities based on the dataset (available online & Manual) and classify them. Further, based on this classification, suggestions can be shared to the user to improve the lifestyle for better health. We first tested without classes later on we added classes, tested and performed encapsulation. 

## Human Activity Recognition

Human activity recognition is a broad field of study concerned with identifying the specific movement or action of a person based on sensor data. Movements are often typical activities performed indoors, such as walking, talking, standing, and sitting. The sensor data may be remotely recorded, such as video, radar, or other wireless methods. Alternately, data may be recorded directly on the subject such as by carrying custom hardware or smart phones that have accelerometers and gyroscopes.
Sensor data for activity recognition was challenging and expensive to collect, requiring custom hardware. Now smart phones and other personal tracking devices used for fitness and health monitoring are cheap and ubiquitous. As such, sensor data from these devices is cheaper to collect, more common, and therefore is a more commonly studied version of the general activity recognition problem. The problem is to predict the activity given a snapshot of sensor data, typically data from one or a small number of sensor types. 


## Explanation of our Project

In our Python Project, we collected data from two sources: an online dataset and our smartwatch. We compared our dataset to one available online. We noted heart rate and step count from our dataset. The user entered the heart rate, the step count was selected from our dataset, and the index number was recorded. In our project, we compared the calories and step count of the dataset acquired from our watch and online, and any null values were eliminated. The rows where the dataset matched were segregated from the remainder of the rows in DF, which is our dataset derived from watch step counts, and in DA, which is derived from the online data. A chart is created based on the analysis of two factors: calories and step count. The comparison of the two elements is represented by a scatter and pie chart. The pie chart also displays the user's active and idle minutes. After all of this, the user's heart rate is compared to the mean heart rate; if the value of the user's heart rate is greater than the total value of mean heart rate + 10, it indicates that the heart rate is abnormal and the user should consult a doctor; if the value of user's heart rate is less than the value of mean heart rate + 10, it indicates that the heart rate is normal and the you are good to go. Hence, the consultation from doctor is noted.



## Analysis between calories and step count using Line Graph

![python](https://user-images.githubusercontent.com/78655015/187520824-eef698e8-9bf8-4da2-90e4-5e77f33b2037.png)


## Analysis between calories and step count using scatter Graph

![unnamed (1)](https://user-images.githubusercontent.com/78655015/187521642-1451100c-a745-4c97-88e2-a834c8430517.png)


## Analysis Between Active Minutes & Inactive Minutes Using PIE CHART

![pythonnn](https://user-images.githubusercontent.com/78655015/187523729-773f2016-0d1e-4c84-990e-7fba49c86df2.png)






Dataset_final:
https://drive.google.com/file/d/1dHc_YA02HwAUrP-l4HbkZBUHk3YNnGOB/view?usp=sharing

Dataset_for_graphs:
https://drive.google.com/file/d/1ugm6c_1rAu4JY8A6yik6N3dpcjCXHcP7/view?usp=sharing

