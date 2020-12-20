# IRB7600
Model of IRB7600 robot with Denavit-Hartenberg parameters (RB7600.urdf) and with modfified Denavit-Hartneberg parameters (RB7600v2.urdf)  
Based on http://wiki.ros.org/urdf_tutorial
## How to launch
<ol>
<li>create catkin workspace</li>
<li>clone this repo to the src directory</li>
<li>go back to catkin worksapce, type `catkin_make` </li>
<li>switch to this repsoitory folder and launch with `roslaunch IRB7600 display.launch model:=urdf/IRB7600v2.urdf`
</li>
<li>To see joints positions `rosrun tf tf_echo /base_link /tool or /base_link or /tool` with other link name</li>
</ol>
