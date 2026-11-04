# rviz_social_nav_plugins

RViz 2 plugins for social navigation experiments (ROS 2 Humble), extracted from
[gazebo_test](https://github.com/PIC4SeR/gazebo_test) with their history.

- `rviz_people_display`: display for `people_msgs/People`, with heading and velocity arrows.
- `rviz_goal_pose_annotator`: panels to annotate goal poses and build semantic-map YAML files
  for experiment definitions.

Both are colcon packages; build them in a ROS 2 workspace as usual. In gazebo_test this repo
is mounted as the `rviz_plugins/` submodule.
