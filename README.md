# ECSE 373 Laboratory # 6

## About

This repository relies on the ARIAC 2019 environment which you can read more about at https://bitbucket.org/osrf/ariac/wiki2019/Home. It uses inverse kinematics to return solutions to queiries that require movement of robot arms. See `https://github.com/cheezofsandwich/ecse373_f23_nat65_lab5` for the first portion of this project. Follow the setup instructions in that README for details on cloning the repositories and setting up the necessary workspaces.

## Set up

Upon download, this folder should be renamed to ik_service. This is due to a logistical erorr in naming the repo. It should be located in the ariac_project_ws.

You should be using ROS noetic. Before using this repository, clone the following repositories:
1. `https://github.com/cwru-eecs-373/cwru_ariac_2019.git`
2. `https://github.com/cwru-eecs-373/ecse_373_ariac.git`

## Running the Service

To launch the service:
```
roslaunch ik_service ik_service.launch
```

After the service has been launched:
```
rosrun ik_service ik_client
```

The outputs should read that the service is running, and the number of solutions generated.

