# ROS Custom Controller
Created a custom ROS controller that sends specific commands to manipulator joints.

 To launch the custom controller, type the following command:
```
roslaunch my_controller my_controller.launch
```

To find the custom controller in the controllers list, execute:
```
rospack plugins --attrib=plugin controller_interface | grep my_controller
```


![Robot Arm](https://i.ibb.co/KrrFTb4/Screenshot-at-Jul-03-11-55-23.png)
