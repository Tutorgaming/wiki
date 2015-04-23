# Cheatsheet

## PR2

###Gripper

Open the gripper
```rostopic pub r_gripper_controller/command pr2_controllers_msgs/Pr2GripperCommand "{position: 0.088, max_effort: 100.0}"```

Close the gripper
```rostopic pub r_gripper_controller/command pr2_controllers_msgs/Pr2GripperCommand "{position: 0.0, max_effort: 100.0}"```
