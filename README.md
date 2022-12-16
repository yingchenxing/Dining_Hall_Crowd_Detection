# Dining_Hall_Crowd_Detection
**Server side backend**
> https://github.com/yingchenxing/Dining_Hall_Crowd_Detection-Backend

**Web application**
> https://github.com/yingchenxing/Dining_Hall_Crowd_Detection_Front_End

**Mobile application**
> https://github.com/yingchenxing/Dining_Hall_Crowd_Detection-Android

## ABOUT THE PROJECT
At Virginia Tech, students have many responsibilities, commitments, and additional personal matters they will attend throughout the day. What makes up the heavy traffic within the dining halls include students waiting on food, ordering food, eating, students socializing, and students attempting to mauvere through others to find a seat. This makes going to the dining halls for students a hassle in some cases due to the amount of time it will cost.  Students should not have to plan around an extra 30 minutes to an hour or so just to get food for themselves when they have other responsibilities as well. With all this in mind, we want to derive a solution that accommodates these components in the chosen problem. 

## PROGRAMMING SUMMARY
we have developed a system that can monitor the number of people in the dining halls in real-time. This system will identify the number of customers through surveillance cameras deployed with the YOLOv5 model and send the real-time data to the server. The server receives the data and stores it in a local SQL database. Customers can use the mobile application to know how crowded each dining hall is. The staff can control the open status of the dining halls via web application.

  
### YOLOv5 model
<img width="959" alt="1670185045827" src="https://user-images.githubusercontent.com/71536778/205512897-9ecc0d0a-6535-4336-bf3f-ccd2a6b44a1a.png">
<img width="959" alt="1670185045827" src="https://user-images.githubusercontent.com/71536778/205512902-6018276a-2866-4541-91a0-45d7d573de9a.png">


### Mobile application
By using the api provided by the server side to get the real time data, the app can render the data and show on the front end.
This application allows you to check the occupancy of the dining halls in real-time, so you can plan your meals and avoid crowded dining halls.

To use the application, simply open it and you will see a list of the available dining halls. Each dining hall is displayed with its current occupancy level, which is updated in real-time. You can also see the open status of each dining hall.

To view more information about a specific dining hall, simply tap on its name. This will open a detailed view with additional information such as the capacity of the dining hall and the percentage of occupancy.

We hope this application helps you have a better dining experience on campus. If you have any feedback or suggestions, please don't hesitate to contact us.
<img width="300" alt="" src="https://user-images.githubusercontent.com/71536778/205512931-c9daf3a1-a9e3-4389-8094-cf9f4e75b52f.gif">

### Web application
We also built a web application by using Vue.js framework for the dining hall staff.

This application allows you to view and manage the occupancy of the dining halls in real-time.

To use the application, simply log in with your authorized credentials. Once logged in, you will see a dashboard with a list of the available dining halls. Each dining hall is displayed with its current occupancy level, which is updated in real-time.

From the dashboard, you can also view detailed information about each dining hall, including its capacity and the percentage of occupancy. You can also control the open status of each dining hall from the dashboard.

We hope this application helps you have a better dining experience on campus. If you have any feedback or suggestions, please don't hesitate to contact us.
<img width="959" alt="1670185045827" src="https://user-images.githubusercontent.com/71536778/205513439-c2d39e6c-66ee-4a27-8cbb-3e0cea97a477.png">


