# ShanghaiTech University SI100B Project: RoboWriter
## Introduction
This is a README file for **ShanghaiTech University SI100B Project: RoboWriter**. This file explains the requirements and grading criteria of the project, including project implementations, project reports, and project presentations. Please read throughout this file and make sure you have a group member with Windows platform before starting the project.

## Project Implementations
### Requirements
#### Basic
1. Robot Arm Model (5 points): The universal_robots_ur5e model in the newest version of code repo : https://github.com/MAYBERoboLab/SIST_SI100B_RoboWriter 
2. Start pose and Terminal pose (5 points): The robot arm can start at any pose but needs to stop at the joint configuration: $[0.0,-2.32,-1.38,-2.45,1.57,0.0]$ rad after finishing the writing.
3. Writing area (5 points): The writing area is a square at the plane z=0.1 m. This square is defined by its four vertices: $(0.5, 0.1, 0.1)$, $(0.5, 0.6, 0.1)$, $(-0.5, 0.6, 0.1)$, and $(-0.5, 0.1, 0.1)$ m.
4. Lifting the end-effector (5 points): The end-effector of the robot arm should lift between each stroke and each character.
5. Writing contents (5 points): The robot should write a student's name in Chinese and PinYin, and the student's school ID in the writing area.
6. Writing speed (5 points): The robot's writing speed should be set at a reasonable value so that the whole writing time (from the robot's start pose to the terminal pose) is less than 3 minutes.
7. Interpolation Method (10 points): Use different interpolation methods to mimic the real strokes.
8. Demo video (5 points): Record a video to demonstrate the writing process, you can adjust the camera for a better view. The name of the video should be "Group Member Names + Final Project Demo" in MP4 format.
#### Bonus
1. Git (1 point): Use Git to manage your code, and you need to have at least 3 commits for each group member.
2. Writing arbitrary words (2 points): Given an arbitrary string, you need to write the words in the string with the robot arm. The string will only contain English letters, spaces, numbers, commas, and periods.
3. Writing on a sphere (3 points): Write words on an area of the inner surface of a sphere defined by: $(x-0)^2+(y-0.35)^2+(z-1.3)^2=0$ and $z\leq 0.1$.
### Grading Criteria
1. For basic requirements, if you will only earn the points from requirement 1 to $k (k=1,2,3,4,5,6,7)$ if you fail to finish requirement $k+1$. If you fail to finish multiple requirements, $k$ will be the smallest requirement index that was not completed.
2. For basic requirement 7, you will earn 3 points if you only use linear interpolation.
3. The bonus tasks can be completed in any combination

## Project Reports
### Requirements
**TBD**
### Grading Criteria
**TBD**

## Project Presentations
### Requirements
**TBD**
### Grading Criteria
**TBD**