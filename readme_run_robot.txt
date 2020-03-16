apt install ros-melodic-joy-teleop ros-melodic-teleop-tools ros-melodic-teleop-twist-joy ros-melodic-teleop-twist-keyboard

1. 啟動底盤 roslaunch base_control base_control.launch

jstest /dev/input/js0 確定搖桿有輸入

2. 啟動joy node:  rosrun joy joy_node 

3.啟動搖桿：rosrun teleop_twist_joy teleop_node 
 

