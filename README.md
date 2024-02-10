this is a guide in order to run the nodes for the second homework of the intelligent robotics course.

1. roslaunch tiago_iaslab_simulation start_simulation.launch world_name:=ias_lab_room_full_tables
2. roslaunch tiago_iaslab_simulation apriltag.launch 
3. roslaunch tiago_iaslab_simulation navigation.launch
4. rosrun tiago_iaslab_simulation human_node
5. rosrun tiago_iaslab_simulation Servernode
6. rosrun tiago_iaslab_simulation node_A
7. rosrun tiago_iaslab_simulation node_B
8. rosrun tiago_iaslab_simulation node_C
