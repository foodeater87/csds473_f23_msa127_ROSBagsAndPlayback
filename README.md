# Lab 3: ROS Bags and Playbacks
## Step 1: Download Map Dependency (All Other Dependencies Were Downloaded for the Navvis Description Lab)
## Step 2: Clone Navvis-Description Repository (Lab 2) into the ROS Configured Workspace
Clone the following link: 
https://github.com/foodeater87/csds_473_f23_msa127_navvis_description
## Step 3: Clone the Maps into the ROS Configured Workspace
Use the following link:
https://github.com/cwru-eecs-373/maps_glennan.git
## Step 4: Download the Bag File
Download the basic short version of the Glennan 5th floor bag file
## Step 5: Edit the Launch File to Find the Bag File
Modify the path on line 11 of displayL3.launch so that it correctly leads to the bag file downloaded in step 4
## Launch RVIZ to View the Robot and Sensor Data
Use the following command in the workspace:
roslaunch displayL3.launch use_xacro:=true
