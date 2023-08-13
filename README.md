sudo apt-get install -y nlohmann-json3-dev
# unity_pioneer

to create a new map run
```
roslaunch pioneer_navigation2 generate_map.launch.py
```

after the map is done run where ~/map is where the map directory in which the map will be saved.
```
ros2 run nav2_map_server map_saver_cli -f ~/map
```
# ros2_pioneer
