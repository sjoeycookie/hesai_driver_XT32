#系统要求  
1.ubuntu 18.04  
2.PCL库

#使用  
mkdir -p catkin_ws/src   
cd catkin_ws/src  
git clone https://github.com/sjoeycookie/hesai_driver_XT32.git  
cd ..  
catkin_make  
source ./devel/setup.bash  
roslaunch hesai_lidar hesai_lidar.launch  
'''


