# Project presentation
## 1.1 The idea
We wanted to create a robot with practical use, an interesting little robot that can be used in a person's daily life. In our childhood we used to play with manurelly controlled cars and Switsch etc.. So it sounds like a lot of fun to design and build your own little car and be able to control it with a controller.

Once we had assembled and programmed the body of the car, we were able to make the little robot drive straight, turn and reverse using the controller.

In addition to the basic driving functions, we wanted to add a few useful functions to the little robot, such as gripping. So we added a robot hand to one side of the car, which is also controlled by a controller. Now we can control the little robot to walk to a spot in the room, grab the target and bring it back to us.

Now a new question arises: is a robot that can only be controlled manually a real robot? Or is it just a machine?

For this reason, we have equipped our little robot with an automatic sweeping function. We built a vacuum robot part at the other end of the trolley.

Our little robot can now not only be controlled manually, drive and reach, but also has an automatic sweeping function that collects the LEGO pieces scattered on the floor.

## 1.2 Tasks
- Think about what characteristics a small robot must have and sketch them.
- Build prototypes based on sketches.
- Program the small robot.
- Test the small robot and optimize it.
- Document the process and the results of the work and share them with other participants.
## 1.3 Preparation
- Learn software (through https://stackoverflow.com, https://www.youtube.com)

# 2 Handware:
## 2.1 Materials:
     - LEGO® Education SPIKE™ Prime set (45678)
     - LEGO® Education SPIKE™ Prime expansion set (45681)
     - Controller (Sony PS4)
## 2.2 components used:
     - Elements, a light matrix, a distance sensor, 4 motors and a controller
  
       
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%201.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%202.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%203.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Kontrolle.JPG)

## 2.3 3D model to build
    - [File is in the folder Handware](https://github.com/XueruWang233/Lego/blob/main/Hardware/3D%20Model.io)
## 2.4 Construction
    - Side of the robot hand

![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Roboterhand%203.JPG)

    - Side of the vacuum robot

![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Sauberroboter%203.JPG)

# 3 Codes
## 3.1 Software
    - Mindstorms 51515 Robot Inventor (https://apps.microsoft.com/detail/9MTQ0N7W1D6X?hl=en-US&gl=DE)
## 3.2 Source file
    - [File is in the Codes folder](https://github.com/XueruWang233/Lego/blob/main/Codes/Projekt%201.lms)
## 3.3 Codes and their functions
- Manually controlled components (with the controller): When the side with the robot hand is used as the "head"(or so-called front) of the robot, the robot performs a series of actions and movements based on the human's use of the controller.
    - When R2 button is pressed, the robot moves forward.
    - When the D-pad left button is pressed, the robot turns left.
    - When the D-pad right button is pressed, the robot turns right.
    - When the R2 button is released, the robot stops.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Fahren(to%20front)%20and%20turn.png)

    - When the L2 button is pressed, the robot moves backwards.
    - If the left cross-control key is pressed, the robot turns left.
    - When the cross control right button is pressed, the robot turns right.
    - When the L2 button is released, the robot stops.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Ru%CC%88ckfahren%20und%20Abbigen.png)

    - Initialization：In the initial state, the manipulator is in the closed state and the Cat Meow sound effect is playing.
    - When triangle button is pressed, the robot hand opens.
    - When the robot hand is detected in an open state, the hand closes automatically or the robot hand grabs the object, and then the Cat Meow sound effect plays.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Initialisierung(closure)%20of%20Robothands.png)
  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Roboterhand%20kontrollieren.png)

- Automated components: When the side with the vacuum robot is used as the "head"(or so-called front) of the robot, the robot can sweep the Lego elements scattered on the floor under the robot.
    - When the circle button is pressed, the robot functions as a vacuum robot or starts sweeping automatically.
    - If the distance sensor detects an obstacle 30 cm away, the robot turns in a different direction to continue sweeping.
    - The Robot Vacuum Cleaner continues to work until the cross button is pressed.

 ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Programmierung_Sauberroboter.png)

# 4 Status Quo
- When the side of the robot hand is used as the front of the robot, the robot moves straight ahead, turns, moves backwards and grabs things, depending on how the human operates the controller.

- If the side with the suction robot is used as the "head" (or so-called front) of the robot, the robot can sweep the Lego elements that are scattered on the floor under the robot.

# 5 Feedback and reflection
With this project we managed to build our own little robot. It was able to perform the functions we wanted and had some fun elements, such as calling out when its paws opened and closed. This made our little robot more alive and not just a simple remote-controlled car or sweeper, but our friend.

We also learned a lot in the process, starting with the mechanics, such as linkages, gears and so on. Then came the software part, where we learned about programming software other than Python, such as SPIKE and Mindstorms.

What we can still improve is that when our little robot is used as a sweeper, it can't catch the parts but they run out the back. So we need to add another dust collection bag for the small robot.

Another question we are very interested in is the one already mentioned, whether a manually controlled robot can be called a robot. What exactly is the definition of a robot? We will also look into this question in our further studies and research ;)


