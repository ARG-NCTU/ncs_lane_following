# ncs_lane_following

Run with default model (simple loop):
```
$ roslaunch ncs_following ncs_lane_following.launch veh:=duckiebot
```

You can use `model` to specify the model:
```
$ roslaunch ncs_following ncs_lane_following.launch model:=nips_loop.graph veh:=duckiebot
```

* "START" button: NCS lane following
* "BACK" button: Joystick control

