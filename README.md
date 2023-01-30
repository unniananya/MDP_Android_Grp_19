# Multidisciplinary-Design-Project-Android-Application
The android application allows for bluetooth connection to the robot, controls the movement of the robot and tracks the location of the obstacles and the live location of the robot.

## Functionality
1. The android application connects to the Raspberry Pi (RPI) module through bluetooth, which in turn facilitates the connection between the application and the robot. 

![Picture 3](https://user-images.githubusercontent.com/72136295/211238227-ee550e46-3684-4ae7-b9ac-effbbb67d93b.png)

2. The application controls the movement of the robot, allowing it to move forward, backward, right and left. 

![Picture 6](https://user-images.githubusercontent.com/72136295/211237973-ec33ecb6-4c86-4738-ac90-b3736e319830.png)

3. The application displays a virtual arena that allows for marking of 10x10 obstacles and also displays the live location of the robot as it is moving in the arena. 

![Picture 4](https://user-images.githubusercontent.com/72136295/211237888-d61bbba2-b7d5-409e-ab6d-6994bad80279.png)

4. Lastly, the application allows for the transmission of messages to and from the RPI. This includes real-time information like the coordinates of the robot, the image ID of the image identified on the face of the obstacle and the status of the robot

![Picture 5](https://user-images.githubusercontent.com/72136295/211237898-dd42330f-cd91-4a61-a5fd-77ef74fd96fd.png)

## Tasks:
During this module, we were required to compete amongst all the group in the cohort for two task for a positon on the leaderboard: 
1. Task 1: Image Recognition - The first task required the robot to find the shortest path from the coordinates entered into the anroid application. The robot was to proceed to each obstacle, scan the image pasted on the head of the obstacle and send the identified image to the android application. 

<img width="305" alt="Picture 1" src="https://user-images.githubusercontent.com/72136295/211237786-186cdef1-6292-4e2b-a72b-a8a7512e863f.png">
2. Task 2: Fastest Car - The second task required the robot to move forward in a straight line until it reached the first obstacle and identify the first image. Based on this it would either move left or right. This was repeated at the second obstacle and the robot was then required to loop around the second obstacle before parking itself back into the car park. 

<img width="295" alt="Picture 2" src="https://user-images.githubusercontent.com/72136295/211237797-3503d2ce-a9ef-4753-8e69-76d9895262f2.png">

## Ranking
1. Task 1: 2nd of 36 successful groups (Timing: 1min 46s)
2. Task 2: 3rd out of 13 successful groups (Timing: 32s)

## Documentation 
1. The entire MDP process has been documented in the following video: [Video](https://www.youtube.com/watch?v=-sx_L624OJE&list=LL&index=21&ab_channel=Noliferist)

## Teams: 
1. Android: Bachhas Nikita
2. Image Recognition: Goh Tse Yinn, Sheryl and Lam Ting En
3. Algorithm: Lim Jiexian and Yeo Kai Liang, Jasper
4. RPI: Ryan Phuay Qian Hao
5. STM/Robot: Wilson Tee Teo Hong and Yew Fu Yen

## Developed by
1. Bachhas Nikita 
