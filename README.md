# Advanced-Mobile-Robotic-Object-Sorter-v2
An enhanced version of the Advanced mobile robot object sorter v1, featuring a Pixy 2 camera for improved object detection and sorting and a Propeller microcontroller for concurrent task execution.

## WHY IT WAS DEVELOPED
Advanced-Mobile-Robotic-Object-Sorter v2 was developed to improve the initial version 1 by enhancing the robot's object detection and sorting accuracy and exploring concurrent task execution capabilities. This project was part of my advanced mechatronics course in the second year of the Mechanical Engineering master's program at New York University
  
![image](https://github.com/damisotomi/Advanced-Mobile-Robotic-Object-Sorter-v2/assets/67606934/df901d26-7315-44ba-9b46-70816c54d7b4)

  
## HOW IT WORKS
  -This advanced mobile robot sorter v2 has a single mode.
  - The robot moves on a black line using PID control with a QTR 8RC sensor, detects an object using the Pixy 2 camera at a certain distance, picks up the object and continues it 
  - journey to the end of its predefined path and sorts the object based on color detected by the Pixy 2 camera

### MICROCONTROLLER AND PROGRAMMING LANGUAGE USED
  - An A Propeller Microcontroller was used to build this project to allow concurrent task execution.
  - The programming language used was C programming

### Components used
  - Pixy 2 Camera - For object detection and color sorting
  - L298N Motor Driver- To control the DC motors used to control the wheels of the car and also to receive 5v volts from the Arduino for logic circuitry of the wheels 
  - Qtr 8RC Reflectance Sensor array - for line detection and following 
  - Connecting wires
  - Resistors
  - Gripper 3.0 - From parallax website- To grip objects
  - Standard Servo motors- To control the gripper opening and closing mechanism


### Improvements over version 1
  - Replaced the ultrasonic sensor, IR infrared obstacle avoidance sensor, and TCS34725 sensor with a Pixy 2 camera for better obstacle detection and more accurate color sorting.
  - Utilized the Propeller microcontroller to run tasks concurrently on different processors, enhancing performance and reliability.
  - Robot self aligns itself to be at the center of the object and within a certain distance before picking the object after detection by the Pixy 2 camera

### HOW TO USE or RUN
  - Download and unzip the Project2.zip file and open the maincode.side file using the SimpleIDE applicaition
  - Create a black line path using black tape on a white surface for the robot to follow
  - Turn on the power switch of the motor driver of the assembled robot
  - Place an obstacle along the path of the robot visible enough for the Pixy 2 camera to see and the gripper to grip
  - watch as the robot moves along the path and picks up obstacles

### Live demo
https://drive.google.com/file/d/1cc4JW4e6QYrdJFbAJBPed_cZVjnbdwr_/view?usp=sharing
