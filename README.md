GROUP 42 
HILAL URUN, hilal.urun@studenti.unipd.it

INSTRUCTIONS TO RUN THE PROJECT ARE AS FOLLOWS:

cd tiago_public_ws/
source devel/setup.bash
roscore
roslaunch tiago_iaslab_simulation start_simulation.launch world_name:=robotics_library
roslaunch tiago_iaslab_simulation navigation.launch
rosrun tiago_iaslab_simulation Servernode
rosrun tiago_iaslab_simulation Clientnode 10 0 -0.5