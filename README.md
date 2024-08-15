# -Inverse-and-Forward-kinematics_3DoF_Robot
## **Introduction**
Inverse and forward kinematics are concepts in robotics and computer animation that describe the relationship between the joint angles of a robotic or articulated system and the position and orientation of the end-effector (such as a robotic hand or a character's limb).

Forward kinematics uses the joint parameters to compute the configuration of the chain, and inverse kinematics reverses this calculation to determine the joint parameters that achieve a desired configuration.

![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/Inverse-and-Forward-kinematics.jpg)

## **Follow these steps to calculate this:**
##Forward kinematics
Forward movement involves determining the final position of the end effector.
![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/Forward%20kinematics.jpg)

To calculate the forward kinematics,
1- determine the position of the end effector sequentially along the x-axis for each of link 1, link 2, and link 3. Then, I will sum these positions together.
![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/FK1.jpg)
2- I will repeat these steps for the y-axis.
![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/FK2.jpg)

## Inverse kinematics
Inverse kinematics is used to find the angles for link 1, link 2, and link 3.
![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/Inverse%20%20kinematics.jpg)

To calculate the Inverse kinematics,
1-calculated the positions of link 1 and link 2 using the 2DoF in the X and Y axes.
![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/1.jpg)
![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/2.jpg)
2-Calculated the final angle for link 3 by ( angle1 - angle2 ) from the total angle
![Database Table Structure](https://github.com/reham-ali102/-Inverse-and-Forward-kinematics_3DoF_Robot/blob/main/3.jpg)
## **Reference**
  link: /https://www.youtube.com/live/HcEVUetq_sg?feature=shared


