# cv_camera_mod
Add camera auto_exposure setting to original ***cv_camera***.
Now you can set the exposure manually like this:
```
rosrun cv_camera cv_camera_node _cv_cap_prop_auto_exposure:=0.25 _cv_cap_prop_exposure:=0.01
```
Or, set it back to auto_exposure:
```
rosrun cv_camera cv_camera_node _cv_cap_prop_auto_exposure:=0.75
```
