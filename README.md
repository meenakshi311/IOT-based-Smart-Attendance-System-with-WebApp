# IOT-based-Smart-Attendance-System-with-WebApp
# Abstract
Taking attendance manually in class of students consumes a lot of time which could be used for other useful work. Also, manual attendance is not reliable as the chances of people giving proxy attendance are also very high, especially when the strength of the class is high. A Radio Frequency Identification (RFID) based attendance system is discussed here which makes attendance taking much more reliable and less cumbersome. COVID-19 has also made it necessary to ensure that students who show symptoms of the disease like high temperature are not allowed to enter the class. So, a non-contact MLX90614 temperature sensor is also used to accurately monitor the temperature of the students entering the class. Each student is uniquely identified with the help of their RFID tag when it is scanned and details like the Student ID, time, temperature, and date are recorded. The recorded information is sent to a database where it is stored and can later be used. The website and database also make it unnecessary to maintain physical attendance records and monitoring of attendance is much easier than with physical records, apart from being secure. A random forest regressor model has been used to predict future attendance and visualization of trends has been performed.
# Flowchart
![image](https://github.com/meenakshi311/IOT-based-Smart-Attendance-System-with-WebApp/assets/80347426/71906dbe-ae17-4dcc-9426-6b6059ec79b3)
# Hardware Implementation 
![image](https://github.com/meenakshi311/IOT-based-Smart-Attendance-System-with-WebApp/assets/80347426/e2c39c0b-7b60-4bad-a6d7-5aa4620deb93)
# Graphical User Interface
● The XAMPP Control Panel Database is used in this project to build a visual server that stores each student's attendance information. 
● One database was created using the XAMPP Control Panel database named “rfidattendance” which consists of admin, devices, users, and user logs. 
● Information about the students who attended a lecture class is kept in the "users" database. 
● The administration or lecturer uses this information to identify and manipulate each student's attendance data.

![image](https://github.com/meenakshi311/IOT-based-Smart-Attendance-System-with-WebApp/assets/80347426/38c2f550-8fc3-4994-9680-2eb8a6f5da16)

# Data Analytics
● The data analytics part of this project includes marking absence or presence, predicting future attendance, and visualizing the data. 
● We have used Jupyter Notebook for this process. Libraries such as Pandas, Numpy, Matplotlib, and Scikit Learn have been used. ● Assigning presence or absence based on the entry time.

![image](https://github.com/meenakshi311/IOT-based-Smart-Attendance-System-with-WebApp/assets/80347426/18f9b221-1fd3-4bfd-84d7-3491424e17a3)

● Visualizing the number of present vs. absent students every day using a Bar plot.

![image](https://github.com/meenakshi311/IOT-based-Smart-Attendance-System-with-WebApp/assets/80347426/17c505c6-2704-4c5a-a407-4a134ff8f20e)

● Prediction of the next day’s attendance using the Random forest regressor model.

![image](https://github.com/meenakshi311/IOT-based-Smart-Attendance-System-with-WebApp/assets/80347426/fb199208-ca8b-484f-a2a9-047793134882)

# Results
The experimental results show that the proposed system designed for attendance management has provided significant results in managing attendance through the RFID system, and it has revolutionized the method of registering attendance. The web GUI provided gives better clarity of the attendance registered and helps in generating reports as and when needed.







