# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1.open the robot analyzer software.
2.select the robot and its degrees of freedom.
3.change the values with the link length whenever necessary.
4.simulate the model for forward kinematics.
5.pick the graph between the link and the joints.
6.update the Dh parameters of the link configuration and endeffector configuration.




### SIMULATION 
 
### 6DOF
 ![r1](https://user-images.githubusercontent.com/94184828/203837410-e8b75552-575e-4e81-8616-fd77b0f1183f.png)


### 6D0F

![r2](https://user-images.githubusercontent.com/94184828/203837960-62874bae-6334-4401-a65f-2a2ff8e0e60d.png)

 

### 4DOF
 
 ![r3](https://user-images.githubusercontent.com/94184828/203837971-65718737-818e-41a3-a18c-95ece0340c36.png)


### 4DOF

![r4](https://user-images.githubusercontent.com/94184828/203838033-968704b8-bdbe-4451-b408-83ebc05ab479.png)

 ### RESULTS :

Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
