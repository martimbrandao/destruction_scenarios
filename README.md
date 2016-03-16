# destruction_scenarios
This repository contains the source code for the Destruction Scenarios ROS package. The package provides two different destrucion scenarios: a house/building and a garage. Each of these scenarios are available in three forms: easy, intermediate and hard. These "difficulty levels" were chosen according to the level of destruction, i.e., according to the difficulty of transversing the terrain on each level.

These levels have a launch file associated to each one, and use Gazebo to provide the simulation. According to the needs of each user, these launch files can be included in another, user-specified launch file that also launches the robot.

Our goal is to provide a simulation platform where Search and Rescue robot developers can test their robots in common destruction scenarios. We invite anyone to contribute to this package, and we have also made available a different repository with the scripts which were created to generate the scenarios that can be used to generate different ones (this second repository is available at https://github.com/roboptics/destruction_scenarios_generator).
