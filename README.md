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
### 6DOF:
![image](https://user-images.githubusercontent.com/93427201/204087969-864651c2-82ee-4fd4-a9fd-c9a8e2c0f7d9.png)

### 6DOF:
![201601802-da638cb8-37d9-4196-991f-b4291431c5fa](https://user-images.githubusercontent.com/93427201/204087981-42cc4f54-8428-474e-b2d2-079d6a9043e3.png)
 
 ### 4DOF:
![201601870-5e3182c2-0bd3-4f36-98c6-365768cb54d5](https://user-images.githubusercontent.com/93427201/204088506-018bdb4c-cbad-4131-a5ab-c73f3e20c5c6.png)

 ### 4DOF:
 ![201601913-62736240-ccd7-4d47-878f-cc4871f2bfe7](https://user-images.githubusercontent.com/93427201/204088033-370ff585-7ce9-4c3d-90ac-079eeb7e7041.png)
 
### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted..

