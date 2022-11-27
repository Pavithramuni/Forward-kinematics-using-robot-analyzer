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
1.Open the roboanalyzer software.
2.Select the robot and its degree of freedom.
3.Change the values with the link length wherever necessary.
4.Simulate the model for forward kinematics.
5.Plot the graph between the link and the joints.
6.Update the DH parameters of the link configuration and end effector configuration.




### SIMULATION 
![pic1](https://user-images.githubusercontent.com/119229774/204151264-25baaf38-b1bd-467f-843c-35b911168b40.png)
![pic2](https:/![pic3](https://user-images.githubusercontent.com/119229774/204151361-3e9f18ad-2afa-42a1-94f1-788497a381eb.png)

###PLOT
![picture3](https://user-images.githubusercontent.com/119229774/204151418-54b672f7-1754-4a68-892c-cc84896b2b7a.png)
![pic4](https://user-images.githubusercontent.com/119229774/204151465-284995c3-a1be-4264-9cbe-aa51af67ae69.png)
![pic5](https://user-images.githubusercontent.com/119229774/204151533-106a253e-7b6c-48e2-a2dc-6e654aaadc21.png)

![pic6](https://user-images.githubusercontent.com/119229774/204151570-950b90ed-9cc4-4b8d-b02d-35941a0f75cf.png)
###RESULT:
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
