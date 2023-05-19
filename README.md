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


1.open the roboanalyzer software.

2.select the robot and its degree of freedom.

3.change the values with the link length wherever necessary.

4.simulate the model for forward kinematics.

5.plot the graph between the link and the joints.

6.update the DH parameters of the link configuration and the effecrtor configuration.





### SIMULATION 
 
6 DOF

![6dof](https://github.com/NAVEENKUMAR4325/Forward-kinematics-using-robot-analyzer/assets/119479566/77e2ce7d-d091-4f1e-b709-22a4d1e2cf63)

4 DOF

![4Dof](https://github.com/NAVEENKUMAR4325/Forward-kinematics-using-robot-analyzer/assets/119479566/21a009c9-9c32-4410-8a7c-3b611e347cb1)


 
 
 
 
 
 
 ### PLOT 
 
 6DOF:
 
 ![plot 6dof 1](https://github.com/NAVEENKUMAR4325/Forward-kinematics-using-robot-analyzer/assets/119479566/edce2465-b9dc-4599-947c-9ce1adf93da8)
 
 ![plot 6dof 2](https://github.com/NAVEENKUMAR4325/Forward-kinematics-using-robot-analyzer/assets/119479566/c14c6412-e178-4ca4-afc6-70a12f0946b9)
 
 
 4DOF:
 
 ![plot 4dof 1](https://github.com/NAVEENKUMAR4325/Forward-kinematics-using-robot-analyzer/assets/119479566/9190dcfb-5064-400b-af28-d3b547c41b25)
 
 ![plot 4dof 2](https://github.com/NAVEENKUMAR4325/Forward-kinematics-using-robot-analyzer/assets/119479566/d1448de6-f5c7-4dbd-8e2f-c29532494e8e)




 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
