This is a repository for creating a simulation of the rover to be used for training, testing, and development.
## Goals
* The rover and its various sub-systems will be replicated virtually in a simulation. 

* The simulation will interact with the MRCS and ARCS in the same way that the physical rover will. 

* The simulation will facilitate testing and development of the components of the ARCS and MRCS. 

* The operating environment of the rover will be replicated virtually in a simulation. 

## Methodology
* Implement a robust simulation via Gazebo for training and testing 

* We will utilize the simulation software Ignition Gazebo for simulating the rover and its environment. 

* We will create a set of plugins and simulation objects to create the rover in the simulation and enable it to communicate with our control systems via Gazebo-ROS, a package included with Gazebo. 

## Deliverables
* An Ignition Gazebo Simulation of the rover that communicates with control systems in the same way as the physical rover and that can be used to test and train intelligent algorithms. 
