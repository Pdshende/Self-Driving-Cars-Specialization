# Module 2: Graded Quiz
# LATEST SUBMISSION GRADE
# 100%
------------------------------------------------------
1.Question 1
What are the differences between exteroceptive sensors and proprioceptive sensors? (Select all that apply)




- [x] Exteroceptive sensors can determine obstacle size and distance away, whereas proprioceptive sensors cannot.




- [x] Proprioceptive sensors do not interact with the environment, whereas exteroceptive sensors do.

-----------------------------------------------------------------------------

2.Question 2
Which of the following exteroceptive sensors would you use in harsh sunlight?


- [x] Sonar


- [x] Radar

--------------------------------------------------------------------------------

3.Question 3
Why is synchronization and timing accuracy important in the self driving system? Choose the primary reason.


- [x] Synchronization is important to ensure correct sensor fusion.

--------------------------------------------------------------------------------------

4.Question 4
Your autonomous vehicle is driving on the German autobahn at 150 km/h and you wish to maintain safe following distances with other vehicles. Assuming a safe following distance of 2s, what is the distance (in m) required between vehicles? Round your answer to 2 decimal places.
```
83.33
Correct
150*2/3.6
```
-----------------------------------------------------------------------------------------------

5.Question 5
Using the same speed of 150 km/h, what is the braking distance (in m) required for emergency stops? Assume an aggressive deceleration of 5 m/s^2. Round your answer to 2 decimal places.
```
173.61
Correct
(150/3.6)^2/(2*5)
```
-----------------------------------------------------------------------------------------

6.Question 6
Suppose your vehicle was using long range cameras for sensing forward distance, but it is now nighttime and the images captured are too dark. Which of the following sensors can be used to compensate?




- [x] Lidar


- [x] Radar

----------------------------------------------------------------------------------------------------


7.Question 7
What are the differences between an occupancy grid and a localization map? (Select all that apply)


- [x] An occupancy grid uses a dense representation of the environment, whereas a localization map does not need to be dense.


- [x] The localization map is primarily used to estimate the vehicle position, whereas the occupancy grid is primarily used to plan collision free paths.

--------------------------------------------------------------------------------------

8.Question 8
The vehicle steps through the software architecture and arrives at the controller stage. What information is required for the controller to output its commands to the vehicle?



- [x] Planned paths

Correct
The controller commands the vehicle to follow the planned paths.


- [x] Vehicle state

------------------------------------------------------------------------------------------------------

9.Question 9
What is (are) the role(s) of the system supervisor? (Select all that apply)




- [x] To ensure that the maps update at the correct frequencies



- [x] To ensure that the sensors are working correctly

-----------------------------------------------------------------------------------------------------

10.Question 10
Which of the following tasks should be assigned to the local planner?


- [x] Planning to avoid a parked car in the ego vehicle's lane

-------------------------------------------------------------------------------------------------

11.Question 11
What common objects in the environment appear in the occupancy grid?




- [x] Parked vehicles


------------------------------------------------------------------------------------------------

12.Question 12
Which of the following maps contain roadway speed limits?


- [x] Detailed roadmap
-------------------------------------------------------------------------------------------------
