# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
```
open the roboanalyzer software.
select the robot and its degrees of freedom.
change the values of X and Y wherever necessary.
simulate the model for inverse kinematics.
plot the graph between the joints.
update the DH parameters of the link configuration and end effector configuration.
```





### SIMULATION 
 
 RPR ROBOT:


![image](https://github.com/KARTHICKRAJM84/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128134963/a0e9aed6-ea0a-4241-987c-165adc2a5e3a)

 
 ![image](https://github.com/KARTHICKRAJM84/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128134963/0d553723-9481-49d4-a7eb-dc1899870920)

 
 3R ROBOT:
 
 ![image](https://github.com/KARTHICKRAJM84/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128134963/076180e6-c773-46d2-bcd7-5ab9ac4e70af)

 
 
 
 
 
 ### PLOT 
 
 
 RPR ROBOT:
 
 ![image](https://github.com/KARTHICKRAJM84/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128134963/1eeed4c5-b724-4f75-a4a5-619f3db4479f)

 
 
 ![image](https://github.com/KARTHICKRAJM84/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128134963/d3fd8eee-0725-40f1-9683-4fbba7961f37)

 
 
 3R ROBOT:
 

 
 ![image](https://github.com/KARTHICKRAJM84/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128134963/80363edf-7e17-4b5a-b8e7-1b8266dd294b)






![image](https://github.com/KARTHICKRAJM84/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128134963/f76ebe23-7b91-40b0-be19-ff65630db2f8)









### RESULTS :  


Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted
