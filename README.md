# Welcome to Om Prabhu's Github Page


**A little bit about myself:**

I am currently working on a Master's of Engineering at the University of California, Berkeley with a concentration in Control of Robotics and Autonomous Systems. I graduated Summa Cum Laude from Rutgers University with a Bachelor of Science in Mechanical Engineering and a minor in Computer Science. My interests include robotics, electric vehicles, and aerospace and I am looking for full-time opportunities where I can use my technical skills to work on projects that will accelerate humanity into the future! When I am not working, I enjoy playing volleyball, doing crosswords, and participating in trivia contests.


This page contains a portfolio of some of my previous and current projects. I have added links and descriptions for each of them, but feel free to email me any further questions at omprabhu98@gmail.com

## In Progress

**Zendar Capstone Project:** 

For my Master's program, I am currently working on a capstone project with Zendar, a manufacturer of high-definition radar to be utilized on autonomous vehicles. I am leading a team of 4 people to develop an algorithm that will run image segmentation on camera streams and then use this data to identify objects on a radar stream simultaneously. Our team has accomplished implementing image segmentation and monocular depth prediction on videos and is currently trying to retrieve Cartesian coordinates from the depth map. We are using OpenCV in Python and our current progress can be seen at: https://github.com/Mmengyw/Capstone-Updated


## Completed

**Robotics Final Project- SawYeet:** 

My team and I decided to make a Sawyer arm track and hit a ball for the final project for our Introduction to Robotics class. We encountered many difficulties, but overcame them through perseverance and creative problem solving using all available tools on ROS and OpenCV. Our final implementation uses color segmentation to track the ball, Kalman filters for the trajectory, and an internal hashmap for the joint trajectories. In the end, the Sawyer arm was able to track the ball, predict its trajectory, and move to the desired position within 1 second. Overall, it hit the ball 70% of the time, which is much higher than we predicted. We made a website to showcase our results and how we got there at: https://sawyeet.github.io


**Advanced Controls Final Project- Model Predictive Controller for Lane Changing of Autonomous Vehicles:**

For my Advanced Controls class, my team and I designed a model predictive controller to allow for an autonomous vehicle to overtake another vehicle. Our algorithm  finds the optimal trajectory around the obstacle vehicle and then uses the MPC to control the vehicle around this trajectory by minimizing the error around this trajectory. We used Python and Pyomo to solve the constrained finite time optimal control problems and implement the model predictive controller. Our final code is robust enough to allow for different speeds of both the controlled vehicle and obstacle vehicle, a variable starting distance between the two vehicles, and also different shapes of the highway. Our code is available at: https://colab.research.google.com/drive/13JpsTieBLWQWRQIWET8EPDgh4g7r28aw?usp=sharing


**NASA/New Jersey Space Grant Consortium Project:**

Over the summer of 2020, I developed an algorithm in Matlab to assist in the additive manufacturing of aerospace materials and structures for my sponsored NASA/NJSGC project. I created a program in MATLAB that quickly produces and tessellates unit cells of user-inputted sizes and thicknesses that are ready to be printed as STL files, reducing the process for creating .STL files from hours to 5 minutes. I presented my research virtually at the New Jersey Space Grant Consortium Conference, available at https://njsgc.rutgers.edu/posters/2020-summer/om-prabhu-rutgers-university-new-brunswick 
